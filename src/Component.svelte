<script>
    import '../components/my-elements.js';
    function increment(){
        let counter = document.querySelector('my-element');
        counter._increment();
    }
</script>

<div>
    <h1>Hello, World</h1>
    <my-element></my-element>
    <button on:click={increment}>+</button>
</div>