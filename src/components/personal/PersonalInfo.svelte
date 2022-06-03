<script lang="ts">
    const name = "Balázs Almády"
    const birthday = new Date("1990.12.15")
</script>

<section>
    <div class="container">
        <ul>
            <li>Name: {name}</li>
            <li>Birthday: {birthday.toLocaleDateString()}</li>
        </ul>
        
        <img src="assets/profile.jpg" width="200px" alt="Me in the golden hour">
    </div>
</section>