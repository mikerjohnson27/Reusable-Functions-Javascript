<h1>Local Storage Functions</h1>

<details>
    <summary>Retrieve and Display Local Storage</summary>
<p>

```````javascript

   function loadStorage(){
    if(localStorage.getItem((hour) !== null)){
        console.log("local storage is not available.")
    }else{
        const storage = localStorage.getItem(<KeyName>)
        document.querySelector('#am7', 'am9', '#am11', '#1pm', '#3pm', '#5pm').textContent = JSON.parse(storage)
    }
}
loadStorage();

```````

</p>
</details>