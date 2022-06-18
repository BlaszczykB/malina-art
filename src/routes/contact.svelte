<script lang="ts">

</script>

<div class="contact">
    <div class="content-sizing">
        <div class="card">
            <h2>Kontakt</h2>
            <div>
                <div>
                    <div class="contact-line">
                        <img class="icon" src="location.svg" alt="">
                        <p>ul. Malina 1; 60-844 Kraków</p>
                    </div>
                    <div class="contact-line">
                        <img class="icon" src="mail.svg" alt="">
                        <p>test@gmail.com</p>
                    </div>
                    <div class="contact-line">
                        <img class="icon" src="phone.svg" alt="">
                        <p>(48)555-555-555</p>
                    </div>
                </div>
            </div>
                
        </div>
    </div>
</div>

<style>
    .contact {
        background-color: var(--main-background-color);
        min-height: calc(100vh - (var(--header-height) + var(--footer-height)));
        display: flex;
        justify-content: center;
    }

    .contact-line {
        display: flex;
        margin-bottom: 2rem;
    }

    .icon {
        width: 1.5rem;
        margin-right: 3rem;
    }

    .description {
        width: 7rem;
        color: var(--color1);
    }

    .card {
        border: 2px solid var(--gold);
        border-radius: 10px;
        margin: 4rem auto 0 auto;
        padding: 2rem;
        background-color: hsla(0, 0%, 100%, 0.5);
        max-width: 30rem;
    }

    h2 {
        font-family: var(--fancy-font);
        color: #b97f34;
		font-size: 4rem;
        text-align: center;
        margin-bottom: 2rem;
    }

</style>