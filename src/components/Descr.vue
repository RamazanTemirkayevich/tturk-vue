<template>
    <div class="container">
        <section class="description">
            <h2 class="description-title">Description</h2>
            <p class="description-text">Basic slim jeans with a regular fit. Closure and belt loops with contrast
                stitching. The yoke at the back provides a perfect fit on the hips. Aged denim, with bleached spots and
                moderate fading, immediately grabs attention. Slightly narrowed at the bottom, the model tightly fits
                the figure, visually stretches the silhouette and slims. Durable denim is breathable, non-irritating,
                hygroscopic, easy to clean and practical. These jeans are comfortable all day long. A versatile casual
                piece, perfect for city life. Skinny basic jeans look great with fitted shirts and oversized shirts,
                jumpers and T-shirts. Shoes will suit them very different - from sports sneakers and sneakers to lace-up
                boots or brogues. Slim jeans are a practical and comfortable option that should definitely be in your
                wardrobe.</p>
            <h2 class="descr-container-title">Characteristics</h2>
            <div class="descr-container">
                <div class="descr-container-box">
                    <div class="descr-container-block">
                        <div class="descr-container-item">
                            Season..............................................................
                            <span>Demi-season</span>
                        </div>
                        <div class="descr-container-item">
                            Material............................................................
                            <span>Cotton</span>
                        </div>
                        <div class="descr-container-item">Material
                            composition....................................
                            <span>100% cotton</span>
                        </div>
                        <div class="descr-container-item">
                            Collection.........................................................
                            <span>Spring-summer 2020</span>
                        </div>
                        <div class="descr-container-item">Model size in
                            photo.......................................
                            <span>50</span>
                        </div>
                        <div class="descr-container-item">The growth of the model in the photo.....
                            <span>181 cm</span>
                        </div>
                        <div class="descr-container-item">A
                            type................................................................
                            <span>Jeans</span>
                        </div>
                        <div class="descr-container-item">Brand in clothing and footwear.................
                            <span>JeansShop</span>
                        </div>
                    </div>
                    <div class="descr-container-block">
                        <div class="descr-container-item">
                            Season..............................................................
                            <span>Demi-season</span>
                        </div>
                        <div class="descr-container-item">
                            Material............................................................
                            <span>Cotton</span>
                        </div>
                        <div class="descr-container-item">Material
                            composition....................................
                            <span>100% cotton</span>
                        </div>
                        <div class="descr-container-item">
                            Collection.........................................................
                            <span>Spring-summer 2020</span>
                        </div>
                        <div class="descr-container-item">Model size in
                            photo.......................................
                            <span>50</span>
                        </div>
                        <div class="descr-container-item">The growth of the model in the photo.....
                            <span>181 cm</span>
                        </div>
                        <div class="descr-container-item">A
                            type................................................................
                            <span>Jeans</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <div class="descr-mf">
            <div class="descr-title">
                <h2 class="title-name">Description</h2>
                <p class="name-text">Basic slim jeans with a regular fit. Closure and belt loops with contrast
                stitching. The <span class="toggle-text">yoke at the back provides a perfect fit on the hips. Aged denim, with bleached spots and
                moderate fading, immediately grabs attention. Slightly narrowed at the bottom, the model tightly fits
                the figure, visually stretches the silhouette and slims. Durable denim is breathable, non-irritating,
                hygroscopic, easy to clean and practical. These jeans are comfortable all day long. A versatile casual
                piece, perfect for city life. Skinny basic jeans look great with fitted shirts and oversized shirts,
                jumpers and T-shirts. Shoes will suit them very different - from sports sneakers and sneakers to lace-up
                boots or brogues. Slim jeans are a practical and comfortable option that should definitely be in your
                wardrobe.</span></p>
                <a class="open-text" href="#">Expand description</a>
            </div>

            <hr class="line">

            <div class="characteristic">
                <h2 class="char-name">Characteristics</h2>
                <p>Season <br> <span>Demi-season</span></p>
                <hr class="line">
                <p>Material <br> <span>Cotton</span></p>
                <hr class="line">
                <p class="shaddow">Material composition <br> <span>100% cotton</span></p>
                <div class="toggle-chars">
                    <hr class="line">
                    <p>Collection <br> <span>Spring-summer</span></p>
                    <hr class="line">
                    <p>Model size in photo <br> <span>50</span></p>
                    <hr class="line">
                    <p>The growth of the model in the photo <br> <span>181 cm</span></p>
                    <hr class="line">
                    <p>A type <br> <span>Jeans</span></p>
                    <hr class="line">
                </div>
                <a class="open-text" href="#">Expand characteristics</a>
            </div>
            <hr class="line">
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.description {
    margin-top: 75px;
    width: 100%;
    height: 607px;
}

.description .description-title {
    font-weight: 500;
    font-size: 28px;
    display: flex;
    align-items: flex-end;
    color: #0A0A0A;
}

.description .description-text {
    margin-top: 25px;
    width: 1100px;
    font-size: 20px;
    font-weight: 200;
    color: #404040;
}

.description .descr-container-title {
    margin-top: 75px;
    font-weight: 500;
    font-size: 28px;
    display: flex;
    align-items: flex-end;
    color: #0A0A0A;
}

.description .descr-container {
    display: flex;
    margin-top: 25px;
    width: 1064px;
    height: 295px;
}

.description .descr-container .descr-container-box {
    display: flex;
    align-items: flex-start;
    width: 1064px;
    height: 238px;
}

.description .descr-container .descr-container-box .descr-container-block {
    display: flex;
    flex-direction: column;
    width: 482px;
    height: 238px;
}

.description .descr-container .descr-container-box .descr-container-block:last-child {
    margin-left: 100px;
}

.description .descr-container .descr-container-box .descr-container-block .descr-container-item {
    font-size: 18px;
    font-weight: 300;
    color: #919191;
}

.description .descr-container .descr-container-box .descr-container-block .descr-container-item span {
    color: #0A0A0A;
}

@media only screen and (min-width: 320px) {
    .description {
        display: none;
    }

    .descr-mf {
        max-width: 290px;
        margin-top: 20px;
    }

    .descr-mf .descr-title .title-name {
        font-weight: 500;
        font-size: 16px;
    }

    .descr-mf .descr-title .name-text {
        margin-top: 15px;
        font-weight: 300;
        font-size: 16px;
        color: #404040;
    }

    .descr-mf .descr-title .name-text .toggle-text {
        display: none;
    }

    .descr-mf .descr-title .open-text {
        display: block;
        width: 133px;
        margin-top: 5px;
        color: #2F76FF;
        border-bottom: 1px dashed #2F76FF;
    }

    .descr-mf .line {
        margin-top: 20px;
        display: block;
        width: 100%;
        border: 1px solid #EEEEEE;
    }

    .descr-mf .characteristic {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        padding-top: 20px;
    }

    .descr-mf .characteristic .toggle-chars {
        display: none;
    }

    .descr-mf .characteristic .open-text {
        display: block;
        width: 156px;
        margin-top: 5px;
        color: #2F76FF;
        border-bottom: 1px dashed #2F76FF;
    }

    .descr-mf .characteristic p, .toggle-chars p {
        padding-top: 10px;
        color: #919191;
    }

    .descr-mf .characteristic p span, .toggle-chars p span {
        color: #0A0A0A;
    }
}

@media only screen and (min-width: 375px) {
    .descr-mf {
        max-width: 100%;
    }

    .descr-mf .descr-title .title-name {
        font-size: 22px;
    }

    .descr-mf .descr-title .name-text {
        font-size: 18px;
    }

    .descr-mf .descr-title .open-text {
        width: 149px;
        font-size: 18px;
    }

    .descr-mf .characteristic .char-name {
        font-size: 22px;
    }

    .descr-mf .characteristic p {
        font-size: 18px;
    }

    .descr-mf .characteristic p span, .toggle-chars p span {
        font-size: 18px;
    }

    .descr-mf .characteristic .open-text {
        width: 174px;
        font-size: 18px;
    }
}

@media only screen and (min-width: 414px) {
    .descr-mf .descr-title .title-name {
        font-size: 24px;
    }

    .descr-mf .descr-title .name-text {
        font-size: 20px;
    }

    .descr-mf .descr-title .open-text {
        width: 166px;
        font-size: 20px;
    }

    .descr-mf .characteristic .char-name {
        font-size: 24px;
    }

    .descr-mf .characteristic p {
        font-size: 20px;
    }

    .descr-mf .characteristic p span, .toggle-chars p span {
        font-size: 20px;
    }

    .descr-mf .characteristic .open-text {
        width: 193px;
        font-size: 20px;
    }
}
</style>
