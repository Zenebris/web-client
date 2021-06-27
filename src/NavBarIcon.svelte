<script>
    export let icon;
</script>

<li>
    <img src={icon} alt="NavbarIcon">
</li>
<style>
    li {
        padding: 10px;
        padding-bottom: 5px;
        padding-top: 5px;
        list-style-type: none;
    }
    li img {
    filter: invert();
    padding: 10px;
    border-radius: 10px;
    transition: background-color 0.23s;
    }
    li img:hover {
        background-color: #ff8e2b;
        padding: 10px;
        border-radius: 10px;
        transition: background-color 0.3s;
    }
@media only screen and (max-width: 380px) {
    li img {
        width: 20px;
        height: 20px;
    }
}

</style>
