<script>
    import '../components/my-elements.js';
    function increment(){
        let counter = document.querySelector('my-element');
        counter._increment();
    }
    export let count = 100;
</script>

<div>
    <h1>Hello, World</h1>
    <my-element count={count}></my-element>
    <button on:click={increment}>+</button>
</div>