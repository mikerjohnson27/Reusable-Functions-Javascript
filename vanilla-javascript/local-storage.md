<h1>Local Storage Functions</h1>
<h4>Replace The Items in the </h4>
<details>
    <summary>Retrieve and Display Local Storage</summary>
<p>

```````javascript

   function loadStorage(){
    if(localStorage.getItem((<KeyName>) !== null)){
        console.log("local storage is not available.")
    }else{
        const storage = localStorage.getItem(<KeyName>)
        document.querySelector(<IDs>).textContent = JSON.parse(storage)
    }
}
loadStorage();

```````

</p>
</details>