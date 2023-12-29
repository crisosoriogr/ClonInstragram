<script>
    import {onMount} from "svelte";
    import Header from '../components/Header.svelte';
    import Main from '../components/Main.svelte';
    import TimeLine from '../components/TimeLine.svelte';
    import Sidebar from '../components/Sidebar.svelte';


    let data={};
    const API="https://api-pugstagram.herokuapp.com/?nickname=jmam&name=Jhon%20Manuel";
    onMount(async () => {
    try {
        const response = await fetch(API);
        const fetchedData = await response.json();
        set(data, fetchedData);  
    } catch (error) {
        console.error('Error fetching data:', error);
        
    }
});

    

</script>



<style>
    @import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,400;1,300&family=Quicksand:wght@300;500;700&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Quicksand:wght@300;500;700&display=swap');
    :global(body){
        background-color: #fafafa;
        color:rgba(38, 38, 38,0.7);
        font-family:"Lato", sans-serif; 
        margin: 0;
        padding: 0;
    }

    :global(h1,h2,h3){
        margin:0;
        padding:0;
        
    }
</style>
 
<Header/>

<Main>
    <TimeLine post={data.posts}/>
    <Sidebar {...data.user}/>
</Main>