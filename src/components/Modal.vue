<template>
    <div class="modal">
        <div class="modal-box">
            <div class="box-container">
                <div class="title-modal">
                    <h1>Write a review</h1>
                    <ModalClose v-if="ModalClose" @click.self="ModalClose = true" />
                </div>
                <div class="stars-block">
                    <p>How would you rate the product</p>
                    <div class="stars">
                        <svg width="48" height="46" viewBox="0 0 48 46" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M21.5086 2.32291L15.8402 13.816L3.15793 15.6649C0.883627 15.9948 -0.0278315 18.7986 1.62147 20.4045L10.7968 29.3455L8.62668 41.9757C8.23606 44.2587 10.6406 45.9687 12.6545 44.901L23.9999 38.9375L35.3454 44.901C37.3593 45.9601 39.7638 44.2587 39.3732 41.9757L37.2031 29.3455L46.3784 20.4045C48.0277 18.7986 47.1163 15.9948 44.842 15.6649L32.1597 13.816L26.4913 2.32291C25.4756 0.274301 22.5329 0.248259 21.5086 2.32291Z" fill="#FAB82B"/>
                        </svg>
                        <svg width="48" height="46" viewBox="0 0 48 46" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M21.5086 2.32291L15.8402 13.816L3.15793 15.6649C0.883627 15.9948 -0.0278315 18.7986 1.62147 20.4045L10.7968 29.3455L8.62668 41.9757C8.23606 44.2587 10.6406 45.9687 12.6545 44.901L23.9999 38.9375L35.3454 44.901C37.3593 45.9601 39.7638 44.2587 39.3732 41.9757L37.2031 29.3455L46.3784 20.4045C48.0277 18.7986 47.1163 15.9948 44.842 15.6649L32.1597 13.816L26.4913 2.32291C25.4756 0.274301 22.5329 0.248259 21.5086 2.32291Z" fill="#FAB82B"/>
                        </svg>
                        <svg width="48" height="46" viewBox="0 0 48 46" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M21.5086 2.32291L15.8402 13.816L3.15793 15.6649C0.883627 15.9948 -0.0278315 18.7986 1.62147 20.4045L10.7968 29.3455L8.62668 41.9757C8.23606 44.2587 10.6406 45.9687 12.6545 44.901L23.9999 38.9375L35.3454 44.901C37.3593 45.9601 39.7638 44.2587 39.3732 41.9757L37.2031 29.3455L46.3784 20.4045C48.0277 18.7986 47.1163 15.9948 44.842 15.6649L32.1597 13.816L26.4913 2.32291C25.4756 0.274301 22.5329 0.248259 21.5086 2.32291Z" fill="#FAB82B"/>
                        </svg>
                        <svg width="48" height="46" viewBox="0 0 48 46" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M21.5085 2.32291L15.8401 13.816L3.15781 15.6649C0.883505 15.9948 -0.0279536 18.7986 1.62135 20.4045L10.7967 29.3455L8.62656 41.9757C8.23594 44.2587 10.6404 45.9687 12.6543 44.901L23.9998 38.9375L35.3453 44.901C37.3592 45.9601 39.7637 44.2587 39.3731 41.9757L37.2029 29.3455L46.3783 20.4045C48.0276 18.7986 47.1161 15.9948 44.8418 15.6649L32.1595 13.816L26.4911 2.32291C25.4755 0.274301 22.5328 0.248259 21.5085 2.32291Z" fill="#EEEEEE"/>
                        </svg>
                        <svg width="48" height="46" viewBox="0 0 48 46" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M21.5085 2.32291L15.8401 13.816L3.15781 15.6649C0.883505 15.9948 -0.0279536 18.7986 1.62135 20.4045L10.7967 29.3455L8.62656 41.9757C8.23594 44.2587 10.6404 45.9687 12.6543 44.901L23.9998 38.9375L35.3453 44.901C37.3592 45.9601 39.7637 44.2587 39.3731 41.9757L37.2029 29.3455L46.3783 20.4045C48.0276 18.7986 47.1161 15.9948 44.8418 15.6649L32.1595 13.816L26.4911 2.32291C25.4755 0.274301 22.5328 0.248259 21.5085 2.32291Z" fill="#EEEEEE"/>
                        </svg>
                    </div>
                </div>
                <div class="form-block">
                    <form action="">
                        <div class="first-input">
                            <p>Advantages</p>
                            <input type="text" placeholder="Product advantages">
                        </div>
                        <div class="second-input">
                            <p>Disadvantages</p>
                            <input type="text" placeholder="Product disadvantages">
                        </div>
                        <div class="thirty-input">
                            <p>Comment</p>
                            <input type="text" placeholder="Comment about product">
                        </div>
                    </form>
                </div>
                <div class="upload-img">
                    <p>Ulpoad product photos</p>
                </div>
                <button class="modal-btn">
                    <span>Send a review</span>
                </button>
            </div>
        </div>
    </div>
</template>

<script>
import ModalClose from './ModalClose.vue'

export default {
    data() {
        return {
            ModalClose: true
        }
    },
    components: {
        ModalClose
    },
    methods: {
        close() {
            this.$emit('close')
        }   
    }
}
</script>

<style scoped>
@media only screen and (min-width: 320px) {
    .modal {
        display: flex;
        align-items: center;
        justify-content: center;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, .4);
        z-index: 2;
        transition: 0.7s;
        overflow-y: auto;
    }

    .modal .modal-box {
        display: flex;
        align-items: center;
        justify-content: center;
        background: #FFFFFF;
        border-radius: 10px;
        width: 300px;
        height: 685px;
    }

    .modal .modal-box .box-container {
        width: 270px;
        height: 630px;
    }

    .modal .modal-box .box-container .title-modal {
        width: 100%;
        display: flex;
        justify-content: space-between;
    }

    .modal .modal-box .box-container .title-modal h1 {
        font-size: 20px;
    }

    .modal .modal-box .box-container .form-block {
        margin-top: 20px;
    }

    .modal .modal-box .box-container .stars-block {
        margin-top: 25px;
    }

    .modal .modal-box .box-container .stars-block p {
        font-size: 16px;
    }

    .modal .modal-box .box-container .stars-block .stars {
        margin-top: 7px;
        display: flex;
        width: 135px;
        justify-content: space-between;
    }

    .modal .modal-box .box-container .stars-block .stars svg {
        width: 22.22px;
        height: 22.22px;
    }

    .modal .modal-box .box-container .stars-block .stars svg path:hover {
        background: #FAB82B;
    }

    .modal .modal-box .box-container .form-block {
        margin-top: 20px;
    }

    .modal .modal-box .box-container .form-block form .first-input p {
        font-size: 16px;
    }

    .modal .modal-box .box-container .form-block form .first-input input {
        padding: 10px 10px 10px 15px;
        margin-top: 7px;
        width: 100%;
        height: 45px;
        font-size: 16px;
        background: #FFFFFF;
        border: 2px solid #EEEEEE;
        box-sizing: border-box;
        border-radius: 7px;
    }

    .modal .modal-box .box-container .form-block form .first-input input:hover {
        border: 2px solid #2F76FF;
    }

    .modal .modal-box .box-container .form-block form .second-input {
        margin-top: 20px;
    }

    .modal .modal-box .box-container .form-block form .second-input input {
        padding: 10px 10px 10px 15px;
        margin-top: 7px;
        width: 100%;
        height: 45px;
        font-size: 16px;
        background: #FFFFFF;
        border: 2px solid #EEEEEE;
        box-sizing: border-box;
        border-radius: 7px;
    }

    .modal .modal-box .box-container .form-block form .second-input input:hover {
        border: 2px solid #2F76FF;
    }

    .modal .modal-box .box-container .form-block form .thirty-input {
        margin-top: 20px;
    }

    .modal .modal-box .box-container .form-block form .thirty-input input {
        padding: 15px 10px 114px 15px;
        margin-top: 7px;
        width: 100%;
        height: 135px;
        font-size: 16px;
        background: #FFFFFF;
        border: 2px solid #EEEEEE;
        box-sizing: border-box;
        border-radius: 7px;
    }

    .modal .modal-box .box-container .form-block form .thirty-input input:hover {
        border: 2px solid #2F76FF;
    }

    .modal .modal-box .box-container .upload-img {
        margin-top: 20px;
    }

    .modal .modal-box .box-container .modal-btn {
        margin-top: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 50px;
        background: #2F76FF;
        border-radius: 5px;
        border: none;
    }

    .modal .modal-box .box-container .modal-btn span {
        font-size: 18px;
        color: #FFFFFF;
    }
}

@media only screen and (min-width: 1024px) {
    .modal {
        display: flex;
        align-items: center;
        justify-content: center;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, .4);
        z-index: 2;
        transition: 0.7s;
        overflow-y: auto;
    }

    .modal .modal-box {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 600px;
        height: 755px;
        background: #FFFFFF;
        border-radius: 10px;
    }

    .modal .modal-box .box-container {
        width: 500px;
        height: 677.74px;
    }

    .modal .modal-box .box-container .title-modal {
        width: 100%;
        display: flex;
        justify-content: space-between;
    }

    .modal .modal-box .box-container .title-modal h1 {
        font-size: 28px;
    }

    .modal .modal-box .box-container .form-block {
        margin-top: 25px;
    }

    .modal .modal-box .box-container .stars-block {
        margin-top: 50px;
    }

    .modal .modal-box .box-container .stars-block p {
        font-size: 18px;
    }

    .modal .modal-box .box-container .stars-block .stars {
        margin-top: 7px;
        display: flex;
        width: 270px;
        justify-content: space-between;
    }

    .modal .modal-box .box-container .stars-block .stars svg {
        width: 48px;
        height: 46px;
    }

    .modal .modal-box .box-container .stars-block .stars svg path:hover {
        background: #FAB82B;
    }

    .modal .modal-box .box-container .form-block {
        margin-top: 25px;
    }

    .modal .modal-box .box-container .form-block form .first-input p {
        font-size: 18px;
    }

    .modal .modal-box .box-container .form-block form .first-input input {
        padding: 10px 10px 10px 15px;
        margin-top: 7px;
        width: 100%;
        height: 45px;
        font-size: 16px;
        background: #FFFFFF;
        border: 2px solid #EEEEEE;
        box-sizing: border-box;
        border-radius: 7px;
    }

    .modal .modal-box .box-container .form-block form .first-input input:hover {
        border: 2px solid #2F76FF;
    }

    .modal .modal-box .box-container .form-block form .second-input {
        margin-top: 25px;
    }

    .modal .modal-box .box-container .form-block form .second-input input {
        padding: 10px 10px 10px 15px;
        margin-top: 7px;
        width: 100%;
        height: 45px;
        font-size: 16px;
        background: #FFFFFF;
        border: 2px solid #EEEEEE;
        box-sizing: border-box;
        border-radius: 7px;
    }

    .modal .modal-box .box-container .form-block form .second-input input:hover {
        border: 2px solid #2F76FF;
    }

    .modal .modal-box .box-container .form-block form .thirty-input {
        margin-top: 25px;
    }

    .modal .modal-box .box-container .form-block form .thirty-input input {
        padding: 15px 10px 114px 15px;
        margin-top: 7px;
        width: 100%;
        height: 135px;
        font-size: 16px;
        background: #FFFFFF;
        border: 2px solid #EEEEEE;
        box-sizing: border-box;
        border-radius: 7px;
    }

    .modal .modal-box .box-container .form-block form .thirty-input input:hover {
        border: 2px solid #2F76FF;
    }

    .modal .modal-box .box-container .upload-img {
        margin-top: 25px;
    }

    .modal .modal-box .box-container .modal-btn {
        margin-top: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 250px;
        height: 50px;
        background: #2F76FF;
        border-radius: 5px;
        border: none;
    }

    .modal .modal-box .box-container .modal-btn span {
        font-size: 18px;
        color: #FFFFFF;
    }
}
</style>