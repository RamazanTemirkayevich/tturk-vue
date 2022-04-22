<template>
  <header class="header">
    <div class="header-wrapper">
      <div class="top-nav">
        <div class="top-logo">
          <img src="@/assets/logo.png" alt="">
        </div>
        <ul class="nav-list">
          <li class="nav-item">
            <a class="nav-link" href="#">Sell at Turk</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Help</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Mobile app</a>
          </li>
          <li class="nav-item">
            <div class="dropdown-currency">
              <select class="dropdown-select" name="" id="">
                <option value="">USD</option>
                <option value="">TRY</option>
                <option value="">RUB</option>
              </select>
            </div>
          </li>
          <li class="nav-item">
            <div>
              <select name="" id="">
                <option value=""><img src="" alt=""> English</option>
                <option value="">Russian</option>
                <option value="">Turkish</option>
              </select>
            </div>
          </li>
        </ul>
      </div>
      <div class="header__main">
        <div class="header__logo">
          <img src="@/assets/logo.png" alt="">
        </div>
        <button class="header__button">
          <svg width="24" height="18" viewBox="0 0 24 18" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M6.85715 8.81637C6.85715 8.086 7.44923 7.49392 8.1796 7.49392H22.6776C23.4079 7.49392 24 8.086 24 8.81637C24 9.54674 23.4079 10.1388 22.6776 10.1388H8.1796C7.44923 10.1388 6.85715 9.54674 6.85715 8.81637Z"
              fill="white" />
            <path
              d="M3.42857 8.81633C3.42857 9.79015 2.66106 10.5796 1.71428 10.5796C0.767511 10.5796 0 9.79015 0 8.81633C0 7.8425 0.767511 7.05306 1.71428 7.05306C2.66106 7.05306 3.42857 7.8425 3.42857 8.81633Z"
              fill="white" />
            <path
              d="M6.85715 15.8695C6.85715 15.1391 7.44923 14.547 8.1796 14.547H15.8204C16.5508 14.547 17.1429 15.1391 17.1429 15.8695C17.1429 16.5998 16.5508 17.1919 15.8204 17.1919H8.1796C7.44923 17.1919 6.85715 16.5998 6.85715 15.8695Z"
              fill="white" />
            <path
              d="M3.42857 15.8694C3.42857 16.8432 2.66106 17.6327 1.71428 17.6327C0.767511 17.6327 0 16.8432 0 15.8694C0 14.8956 0.767511 14.1061 1.71428 14.1061C2.66106 14.1061 3.42857 14.8956 3.42857 15.8694Z"
              fill="white" />
            <path
              d="M6.85715 1.76326C6.85715 1.0329 7.44923 0.440817 8.1796 0.440817H22.6776C23.4079 0.440817 24 1.0329 24 1.76326C24 2.49363 23.4079 3.08571 22.6776 3.08571H8.1796C7.44923 3.08571 6.85715 2.49363 6.85715 1.76326Z"
              fill="white" />
            <path
              d="M3.42857 1.76326C3.42857 2.73709 2.66106 3.52653 1.71428 3.52653C0.767511 3.52653 0 2.73709 0 1.76326C0 0.78944 0.767511 0 1.71428 0C2.66106 0 3.42857 0.78944 3.42857 1.76326Z"
              fill="white" />
          </svg>
        </button>
        <div class="header__search">
          <form class="search-form" action="">
            <div class="search-input-wrapper">
              <div class="search-inside">
                <input placeholder="Search in Turk" class="search-input" type="text">
                <button class="search-inside__btn">
                  <select class="header__select" name="" id="">
                    <option value="">Everywhere</option>
                    <option value="">Lorem</option>
                    <option value="">lorem</option>
                  </select>
                </button>
              </div>
            </div>
            <button class="btn-search">
              <span>Search</span>
              <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M8.68407 8.84615L12.6938 13M10.0207 5.61538C10.0207 8.16439 8.02596 10.2308 5.56538 10.2308C3.1048 10.2308 1.11011 8.16439 1.11011 5.61538C1.11011 3.06638 3.1048 1 5.56538 1C8.02596 1 10.0207 3.06638 10.0207 5.61538Z"
                  stroke="white" stroke-width="1.5" />
              </svg>
            </button>
          </form>
        </div>
        <div class="admin">
          <ul class="admin-list">
            <li class="admin-item">
              <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M10 20C7.63223 20 5.3357 19.1577 3.53348 17.6281C3.11031 17.2692 2.71336 16.8713 2.35375 16.4455C0.83582 14.6462 0 12.3573 0 10C0 7.32887 1.04016 4.81766 2.92891 2.92891C4.81766 1.04016 7.32887 0 10 0C12.6711 0 15.1823 1.04016 17.0711 2.92891C18.9598 4.81766 20 7.32887 20 10C20 12.3573 19.1642 14.6463 17.6464 16.4452C17.2866 16.8713 16.8897 17.2692 16.4664 17.6282C14.6643 19.1577 12.3678 20 10 20ZM10 1.25C5.17523 1.25 1.25 5.17523 1.25 10C1.25 12.0627 1.98121 14.0654 3.30895 15.6392C3.62379 16.012 3.97148 16.3605 4.34219 16.675C5.91891 18.0131 7.92816 18.75 10 18.75C12.0718 18.75 14.0811 18.0131 15.6577 16.675C16.0285 16.3605 16.3762 16.0119 16.6912 15.6389C18.0188 14.0654 18.75 12.0627 18.75 10C18.75 5.17523 14.8248 1.25 10 1.25Z"
                  fill="#0A0A0A" />
                <path
                  d="M10 10C7.93223 10 6.25 8.31777 6.25 6.25C6.25 4.18223 7.93223 2.5 10 2.5C12.0678 2.5 13.75 4.18223 13.75 6.25C13.75 8.31777 12.0678 10 10 10ZM10 3.75C8.62148 3.75 7.5 4.87148 7.5 6.25C7.5 7.62852 8.62148 8.75 10 8.75C11.3785 8.75 12.5 7.62852 12.5 6.25C12.5 4.87148 11.3785 3.75 10 3.75Z"
                  fill="#0A0A0A" />
                <path
                  d="M16.0626 17.7767C16.0122 17.7767 15.961 17.7706 15.9099 17.7578C15.5752 17.6737 15.3719 17.3342 15.4559 16.9994C15.5681 16.5524 15.625 16.09 15.625 15.625C15.625 12.567 13.1388 10.0443 10.0823 10.0004L10 10L9.9177 10.0004C6.86117 10.0443 4.375 12.567 4.375 15.625C4.375 16.09 4.43191 16.5524 4.5441 16.9994C4.62813 17.3342 4.42484 17.6737 4.09008 17.7578C3.75531 17.8418 3.41574 17.6386 3.33172 17.3038C3.19453 16.7573 3.125 16.1925 3.125 15.625C3.125 13.8055 3.82879 12.0905 5.10672 10.7957C6.3834 9.50219 8.0866 8.77586 9.90258 8.75047C9.90551 8.75043 9.9084 8.75043 9.91133 8.75043L10 8.75L10.0887 8.75039C10.0916 8.75039 10.0945 8.75039 10.0974 8.75043C11.9134 8.77578 13.6166 9.50215 14.8933 10.7957C16.1712 12.0905 16.875 13.8055 16.875 15.625C16.875 16.1925 16.8055 16.7573 16.6683 17.3038C16.5971 17.5874 16.3424 17.7767 16.0626 17.7767Z"
                  fill="#0A0A0A" />
              </svg>
              <span>Log in</span>
            </li>
            <li class="admin-item">
              <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M19.9961 4.93262C19.9727 4.7175 19.8391 4.52711 19.6393 4.43387L10.2643 0.0588672C10.0967 -0.0192969 9.9032 -0.0192969 9.73566 0.0588672L0.360664 4.43387C0.160898 4.52711 0.0272266 4.71746 0.00382812 4.93262C0.00332031 4.93711 0 4.99695 0 5.00023V15.6252C0 15.8808 0.155586 16.1106 0.392891 16.2055L9.76789 19.9555C9.84238 19.9853 9.92121 20.0002 10 20.0002C10.0788 20.0002 10.1576 19.9854 10.2321 19.9555L19.6071 16.2055C19.8444 16.1106 20 15.8808 20 15.6252V5.00023C20 4.99695 19.9966 4.93707 19.9961 4.93262ZM10 1.31492L17.8025 4.95609L14.798 6.15789L6.84871 2.78555L10 1.31492ZM5.32461 3.4968L13.1506 6.81684L10 8.07707L2.1975 4.95609L5.32461 3.4968ZM1.25 5.92336L9.375 9.17336V18.4521L1.25 15.2021V5.92336ZM10.625 18.4521V9.17336L18.75 5.92336V15.2021L10.625 18.4521Z"
                  fill="#0A0A0A" />
              </svg>
              <span>Orders</span>
            </li>
            <li class="admin-item">
              <svg width="20" height="18" viewBox="0 0 20 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M18.5408 1.90123C17.5543 0.781934 16.1859 0.165527 14.6875 0.165527C12.5802 0.165527 11.246 1.42412 10.4979 2.47998C10.3038 2.75397 10.1386 3.02869 10 3.28721C9.86137 3.02869 9.69629 2.75397 9.50215 2.47998C8.75402 1.42412 7.41984 0.165527 5.3125 0.165527C3.81414 0.165527 2.44566 0.781973 1.45918 1.90127C0.518242 2.969 0 4.399 0 5.92783C0 7.59201 0.649727 9.13986 2.04473 10.7989C3.29148 12.2817 5.08512 13.8102 7.16211 15.5801C7.93605 16.2396 8.73641 16.9216 9.58848 17.6671L9.61406 17.6896C9.72453 17.7863 9.86227 17.8346 10 17.8346C10.1377 17.8346 10.2755 17.7862 10.3859 17.6896L10.4115 17.6671C11.2636 16.9216 12.0639 16.2396 12.838 15.58C14.9149 13.8102 16.7085 12.2818 17.9553 10.7989C19.3503 9.13982 20 7.59201 20 5.92783C20 4.399 19.4818 2.969 18.5408 1.90123ZM12.0779 14.6881C11.4107 15.2566 10.724 15.8417 10 16.4712C9.27602 15.8418 8.58934 15.2567 7.92203 14.688C3.85723 11.2242 1.17188 8.93592 1.17188 5.92783C1.17188 4.68447 1.58613 3.52963 2.33836 2.67607C3.09922 1.81283 4.15543 1.3374 5.3125 1.3374C6.9191 1.3374 7.95766 2.32717 8.54594 3.15748C9.07363 3.90217 9.34898 4.65287 9.44289 4.94104C9.52145 5.18225 9.74633 5.34549 10 5.34549C10.2537 5.34549 10.4786 5.18225 10.5571 4.94104C10.651 4.65287 10.9264 3.90217 11.4541 3.15744C12.0423 2.32717 13.0809 1.3374 14.6875 1.3374C15.8446 1.3374 16.9008 1.81283 17.6616 2.67607C18.4139 3.52963 18.8281 4.68447 18.8281 5.92783C18.8281 8.93592 16.1428 11.2242 12.0779 14.6881Z"
                  fill="#0A0A0A" />
              </svg>
              <span>Deferred</span>
            </li>
            <li class="admin-item">
              <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M6.00407 13.1685H17.0241C18.2737 13.1685 19.293 12.1491 19.293 10.8995V6.26299C19.293 6.25888 19.293 6.25066 19.293 6.24654C19.293 6.23421 19.293 6.22599 19.293 6.21366C19.293 6.20544 19.293 6.19722 19.2889 6.189C19.2889 6.18078 19.2848 6.16845 19.2848 6.16023C19.2848 6.15201 19.2807 6.14378 19.2807 6.13556C19.2766 6.12734 19.2766 6.11912 19.2725 6.10679C19.2684 6.09857 19.2684 6.09035 19.2643 6.08213C19.2602 6.07391 19.2602 6.06569 19.256 6.05747C19.2519 6.04925 19.2478 6.04102 19.2437 6.02869C19.2396 6.02047 19.2355 6.01225 19.2314 6.00814C19.2273 5.99992 19.2232 5.9917 19.219 5.98348C19.2149 5.97526 19.2108 5.97115 19.2067 5.96293C19.2026 5.95471 19.1944 5.94648 19.1903 5.93826C19.1862 5.93004 19.1821 5.92593 19.1738 5.91771C19.1697 5.90949 19.1615 5.90538 19.1574 5.89716C19.1533 5.88894 19.1451 5.88483 19.141 5.87661C19.1368 5.86839 19.1286 5.86428 19.1245 5.86017C19.1163 5.85195 19.1122 5.84784 19.104 5.83961C19.0957 5.8355 19.0916 5.82728 19.0834 5.82317C19.0752 5.81906 19.067 5.81084 19.0587 5.80673C19.0505 5.80262 19.0464 5.79851 19.0382 5.7944C19.03 5.79029 19.0217 5.78618 19.0135 5.77796C19.0053 5.77385 18.9971 5.76974 18.9889 5.76563C18.9806 5.76152 18.9724 5.75741 18.9642 5.7533C18.956 5.74919 18.9478 5.74508 18.9395 5.74096C18.9313 5.73685 18.9231 5.73685 18.9149 5.73274C18.9067 5.72863 18.8943 5.72452 18.8861 5.72452C18.8779 5.72452 18.8697 5.72041 18.8656 5.72041C18.8532 5.7163 18.845 5.7163 18.8327 5.7163C18.8286 5.7163 18.8245 5.71219 18.8162 5.71219L4.84904 3.78441V1.83607C4.84904 1.81552 4.84904 1.79497 4.84493 1.77852C4.84493 1.77441 4.84493 1.7703 4.84082 1.76208C4.84082 1.74975 4.83671 1.73742 4.83671 1.72509C4.8326 1.71276 4.8326 1.70454 4.82849 1.69221C4.82849 1.68399 4.82438 1.67987 4.82438 1.67165C4.82027 1.65932 4.81616 1.64699 4.81205 1.63466C4.81205 1.63055 4.80794 1.62233 4.80794 1.61822C4.80383 1.60589 4.79972 1.59767 4.7915 1.58534C4.78739 1.58122 4.78739 1.573 4.78328 1.56889C4.77917 1.56067 4.77506 1.55245 4.76684 1.54423C4.76273 1.53601 4.75861 1.5319 4.7545 1.52368C4.75039 1.51546 4.74628 1.51135 4.74217 1.50313C4.73806 1.49491 4.72984 1.48669 4.72573 1.47846C4.72162 1.47435 4.71751 1.47024 4.7134 1.46613C4.70518 1.45791 4.69696 1.44969 4.68874 1.44147C4.68463 1.43736 4.68052 1.43325 4.67641 1.42914C4.66819 1.42092 4.65996 1.4127 4.64763 1.40448C4.64352 1.40037 4.6353 1.39626 4.63119 1.39215C4.62297 1.38392 4.61475 1.37981 4.60653 1.37159C4.5942 1.36337 4.58187 1.35515 4.57365 1.35104C4.56954 1.34693 4.56543 1.34693 4.56132 1.34282C4.54487 1.3346 4.52432 1.32638 4.50788 1.31816L1.4785 0.0439301C1.19489 -0.075272 0.870163 0.0562613 0.750961 0.33988C0.631759 0.623498 0.763293 0.948221 1.04691 1.06742L3.73512 2.2019V4.71747V5.11618V8.17433V10.9078V14.3605C3.73512 15.5114 4.59831 16.465 5.71223 16.6089C5.51082 16.946 5.39162 17.3406 5.39162 17.7598C5.39162 18.997 6.39867 20 7.63179 20C8.86492 20 9.87197 18.9929 9.87197 17.7598C9.87197 17.3488 9.76099 16.9583 9.56369 16.6295H14.5537C14.3564 16.9624 14.2454 17.3488 14.2454 17.7598C14.2454 18.997 15.2525 20 16.4856 20C17.7188 20 18.7258 18.9929 18.7258 17.7598C18.7258 16.5267 17.7188 15.5196 16.4856 15.5196H6.00407C5.36285 15.5196 4.84493 14.9976 4.84493 14.3605V12.8561C5.18199 13.0534 5.5807 13.1685 6.00407 13.1685ZM8.76627 17.7557C8.76627 18.3805 8.25658 18.8861 7.6359 18.8861C7.01523 18.8861 6.50554 18.3764 6.50554 17.7557C6.50554 17.135 7.01523 16.6253 7.6359 16.6253C8.25658 16.6253 8.76627 17.1309 8.76627 17.7557ZM17.6201 17.7557C17.6201 18.3805 17.1104 18.8861 16.4897 18.8861C15.8691 18.8861 15.3594 18.3764 15.3594 17.7557C15.3594 17.135 15.8691 16.6253 16.4897 16.6253C17.1104 16.6253 17.6201 17.1309 17.6201 17.7557ZM17.0241 12.0587H6.00407C5.36285 12.0587 4.84493 11.5366 4.84493 10.8995V8.16611V5.10796V4.90244L18.1832 6.73979V10.8954C18.1832 11.5408 17.6612 12.0587 17.0241 12.0587Z"
                  fill="#0A0A0A" />
              </svg>
              <span>Shop cart</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

.header {
  width: 100%;
  height: 110px;
  left: 0px;
  top: 0px;
  background: #FAFAFA;
}

.header .header-wrapper {
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}

.header .header-wrapper .top-nav {
  display: flex;
  justify-content: end;
  margin-right: 45px;
  align-items: center;
  height: 35px;
}

.header .header-wrapper .top-nav .top-logo {
  display: none;
}

.header .header-wrapper .top-nav .nav-list {
  display: flex;
  justify-content: end;
  align-items: center;
}

.header .header-wrapper .top-nav .nav-list .nav-item {
  display: flex;
  align-items: center;
  padding: 10px;
}

.header .header-wrapper .top-nav .nav-list .nav-item select {
  border: none;
  background: #fafafa;
}

.header .header-wrapper .top-nav .nav-list .nav-item .nav-link {
  text-decoration: none;
  color: #0A0A0A;
  font-size: 14px;
}

.header .header-wrapper .header__main {
  display: flex;
  justify-content: center;
  align-items: center;
}

.header .header-wrapper .header__main .header__button {
  margin-left: 15px;
  width: 75px;
  height: 39px;
  background-color: #2F76FF;
  border-radius: 5px;
  border: none;
  cursor: pointer;
}

.header .header-wrapper .header__main .header__search {
  margin-left: 15px;
  border-radius: 5px;
  max-width: 582px;
  width: 100%;
}

.header .header-wrapper .header__search .search-form {
  display: flex;
}

.header .header-wrapper .header__search .search-input-wrapper {
  width: 100%;
}

.header .header-wrapper .header__search .search-inside {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 35px;
  border: 2px solid #2F76FF;
  background: #fff;
  border-radius: 5px;
}

.header .header-wrapper .header__search .search-inside .search-inside__btn {
  width: 110px;
  height: 31px;
  background: #EBF2FF;
  border-radius: 5px;
  border: none;
}

.header .header-wrapper .header__search .search-inside .search-inside__btn .header__select {
  border: none;
  background: #EBF2FF;
}

.header .header-wrapper .header__search .search-input {
  text-indent: 15px;
  border: none;
  outline: none;
  width: 274px;
}

.header .header-wrapper .header__search .btn-search {
  display: flex;
  align-items: center;
  width: 98px;
  background: #2F76FF;
  border-radius: 0px 5px 5px 0px;
  font-size: 14px;
  color: #ffff;
  border: none;
}

.header .header-wrapper .header__search .btn-search span {
  margin-left: 1em;
  padding: 2px;
}

.header .header-wrapper .admin {
  margin-left: 33px;
}

.header .header-wrapper .admin .admin-list {
  display: flex;
  flex-direction: row;
  align-items: baseline;
}

.header .header-wrapper .admin .admin-list .admin-item {
  padding: 10px 14px;
  text-align: center;
}

.header .header-wrapper .admin .admin-list .admin-item span {
  font-size: 12px;
  font-weight: 400;
  display: block;
  margin-top: 1px;
  color: #0A0A0A;
}

@media only screen and (min-width: 320px) {
  .header {
    display: flex;
    align-items: center;
    width: 100%;
    height: 120px;
  }

  .header .header-wrapper .top-nav {
    justify-content: flex-start;
  }

  .header .header-wrapper .top-nav .top-logo {
    display: block;
    padding: 16px;
  }

  .header .header-wrapper .top-nav .nav-list {
    display: none;
  }

  .header .header-wrapper .header__main .header__logo {
    display: none;
  }

  .header .header-wrapper .header__main .header__button {
    display: none;
  }

  .header .header-wrapper .header__main .header__search {
    padding-top: 15px;
    width: 290px;
    margin-left: 0;
  }

  .header .header-wrapper .header__search .search-input {
    width: 145px;
  }

  .header .header-wrapper .header__search .search-inside .search-inside__btn {
    width: 101px;
  }

  .header .header-wrapper .header__search .btn-search {
    width: 45px;
    justify-content: center;
  }

  .header .header-wrapper .header__search .btn-search span {
    display: none;
  }

  .header .header-wrapper .admin {
    display: none;
  }

}
</style>
