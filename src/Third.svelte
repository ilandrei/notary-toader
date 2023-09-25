<script>
    import Instagram from "svelte-material-icons/Instagram.svelte";
    import Whatsapp from "svelte-material-icons/Whatsapp.svelte";
    import Phone from "svelte-material-icons/Phone.svelte";
    import Email from "svelte-material-icons/Email.svelte";
    import MapMarker from "svelte-material-icons/MapMarker.svelte";
    import ClockTimeNine from "svelte-material-icons/ClockTimeNine.svelte";
</script>

<div class="page-container">
    <div class="background-container" />
    <div class="page-gradient" />
    <div class="page-content">
        <section>
            <div class="first-section-half section-half">
                <h1>Contact</h1>
                <div class="contact-section">
                    <h4 class="contact-section-titlte">
                        <Phone size="24px" color="#4f4f4f" /> Tel/Fax:
                    </h4>
                    <div class="contact-section-detail">
                        <a class="contact-link" href="tel:+40-332-40-14-00">
                            0332/401.400</a
                        >
                    </div>
                </div>

                <div class="contact-section">
                    <h4 class="contact-section-titlte">
                        <Email size="24px" color="#4f4f4f" /> Email:
                    </h4>

                    <div class="contact-section-detail">
                        <a
                            class="contact-link"
                            href="mailto: notar.toader@yahoo.com"
                            >notar.toader@yahoo.com</a
                        >
                    </div>
                </div>
                <div class="contact-section">
                    <h4 class="contact-section-titlte">
                        <MapMarker size="24px" color="#4f4f4f" /> Adresă:
                    </h4>
                    <div class="contact-section-detail">
                        <a
                            class="contact-link"
                            href="https://maps.app.goo.gl/BpjZR8RNDgfjkyex9"
                        >
                            Mun. Iaşi, Str. Anastasie Panu nr. 13, bl. Ghica
                            Vodă 1B, parter, Jud. Iaşi
                        </a>
                        <a
                            class="contact-link"
                            href="https://ul.waze.com/ul?place=ChIJC0NLOU_7ykARLZNRoe3f3gU&ll=47.16018970%2C27.59169890&navigate=yes&utm_campaign=default&utm_source=waze_website&utm_medium=lm_share_location"
                        >
                            (Direcții prin Waze)</a
                        >
                    </div>
                </div>

                <div class="contact-section">
                    <h4 class="contact-section-titlte">
                        <ClockTimeNine size="24px" color="#4f4f4f" /> Program:
                    </h4>
                    <div class="contact-section-detail">
                        <span class="calendar-text"
                            >Luni - Vineri: 9:00 - 17:00</span
                        >
                        <span class="calendar-text">Sambătă : Închis</span>
                        <span class="calendar-text">Duminică : Închis</span>
                    </div>
                </div>
                <h4>Pentru orice detalii nu ezitați să ne contactați!</h4>

                <div class="social-row">
                    <span>Ne găsiți și pe:</span>
                    <a
                        href="https://www.instagram.com/notariat_toader/"
                        class="social-link"
                    >
                        <Instagram size="24px" color="#b76262" />
                    </a>

                    <a href="http://wa.me/+40740566619" class="social-link">
                        <Whatsapp size="24px" color="#b76262" />
                    </a>
                </div>
            </div>
        </section>
    </div>
</div>

<style>
    .calendar-text {
        color: #b76262;
        font-weight: 400;
        margin-bottom: 0;
        font-size: 18px;
    }
    .contact-section-titlte {
        display: flex;
        flex-direction: row;
        align-items: center;
        margin: 0%;
        padding: 0;
    }
    .contact-section {
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        justify-content: flex-start;
        gap: 10px;
        margin-top: 20px;
    }
    .contact-section-detail {
        display: flex;
        flex-direction: column;
    }
    .contact-link {
        color: #b76262;
        font-weight: 400;
        margin-bottom: 0;
        font-size: 18px;
    }
    .social-row {
        display: flex;
        flex-direction: row;
        align-items: center;
        color: #4f4f4f;

        font-size: 20px;
        font-weight: 400;
    }
    .social-link {
        margin-top: 10px;
        margin-left: 10px;
    }
    .background-container {
        z-index: 1;
        background-image: url("https://api.mapbox.com/styles/v1/mapbox/light-v11/static/pin-s+555555(27.5918,47.1598)/27.5904,47.1594,16.95,0/1280x1280?access_token=pk.eyJ1IjoiaWxhbmRyZWkiLCJhIjoiY2xidjkyZXFmMDV4YTNwbzFpdXk3NXh4NiJ9.6kgPKWMg3Sn0bAPNi4JZIQ");
        background-size: cover;

        background-repeat: no-repeat;
        width: 100vw;
        height: 100vh;
        position: absolute;
    }

    .page-content {
        z-index: 3;
        padding: 80px 20px;
        width: 100vw;
        height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        position: absolute;
    }
    .page-gradient {
        z-index: 2;
        position: absolute;
        width: 100vw;
        height: 100vh;

        background: #f8f4f4;
        background: linear-gradient(
            90deg,
            rgba(248, 244, 244, 0.9) 40%,
            rgba(248, 244, 244, 0.2) 60%
        );
    }
    .page-container {
        width: 100vw;
        height: 100vh;
        position: relative;
    }

    section {
        flex-grow: 1;
        width: 95%;
        display: flex;
        flex-direction: row;
        align-items: center;
    }
    h1 {
        font-size: 54px;
        color: #4f4f4f;
        font-weight: 700;
        padding: 0;
        margin: 0;
    }
    h4 {
        color: rgb(79, 79, 79);
        font-weight: 400;
        margin-bottom: 0;
        font-size: 18px;
    }
    a {
        color: #3500d3;
    }

    .first-section-half {
        width: 40%;
        height: 60%;
        border-radius: 5px;
        padding: 10px;
    }
    @media screen and (max-width: 800px) {
        h1 {
            font-size: 46px;
        }
        .page-gradient {
            background: #f8f4f4;
            background: linear-gradient(
                rgba(248, 244, 244, 0.9) 30%,
                rgba(248, 244, 244, 0.6) 60%
            );
        }

        .first-section-half {
            width: 80%;
        }
        section {
            align-items: baseline;
            width: 100%;
        }

        .background-container {
            background-image: url("https://api.mapbox.com/styles/v1/mapbox/light-v11/static/pin-s+555555(27.5918,47.1598)/27.5904,47.1594,16.95,0/1280x1280?access_token=pk.eyJ1IjoiaWxhbmRyZWkiLCJhIjoiY2xidjkyZXFmMDV4YTNwbzFpdXk3NXh4NiJ9.6kgPKWMg3Sn0bAPNi4JZIQ");
        }
    }
    @media screen and (max-width: 600px) {
        h1 {
            font-size: 40px;
        }

        .first-section-half {
            width: 100%;
        }
        .contact-link {
            font-size: 16px;
        }
        h4 {
            font-size: 16px;
        }
        .social-row {
            font-size: 16px;
        }
        .calendar-text {
            font-size: 16px;
        }
        .page-content {
            padding: 80px 10px;
        }
    }
    @media screen and (max-height: 800px) {
        .background-container {
            height: 800px;
        }
        .page-content {
            height: 800px;
        }
        .page-gradient {
            height: 800px;
        }
        .page-container {
            height: 800px;
        }
        section {
            align-items: baseline;
        }
    }
</style>
