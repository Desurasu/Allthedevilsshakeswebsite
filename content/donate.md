<script src="https://donorbox.org/widget.js" paypalExpress="false"></script>

<style>
    .donation-grid {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 1rem;
        width: 100%;
    }

    .donorbox-iframe {
        width: 500px;
        max-height: none !important;
    }

    /* Shrink the donorbox iframes & go to 1 grid column on mobile */
    @media (max-width: 1100px) {
        .donation-grid {
            grid-template-columns: 1fr;
        }

        .donorbox-iframe {
            width: 350px;
        }
    }
</style>

<div class="donation-grid">
    <div>
        <h1>Donations</h1>
        <iframe
            class="donorbox-iframe"
            src="https://donorbox.org/embed/all-the-devils-shakespeare"
            name="donorbox"
            allowpaymentrequest="allowpaymentrequest"
            seamless="seamless"
            frameborder="0"
            scrolling="no"
            width="100%"
            allow="payment">
        </iframe>
    </div>
    <div>
        <h1>Advertisements</h1>
        <iframe
            class="donorbox-iframe"
            src="https://donorbox.org/embed/all-the-devils-shakespeare-playbill-ad-purchasing"
            name="donorbox" allowpaymentrequest="allowpaymentrequest"
            seamless="seamless"
            frameborder="0"
            scrolling="no"
            width="100%"
            allow="payment">
        </iframe>
    </div>
</div>
