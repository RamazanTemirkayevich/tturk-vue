<template>
  <header class="header">
    <div class="header-wrapper">
      <div class="top-nav">
        <div class="top-logo">
          <img src="@/assets/logo.png" alt="">
        </div>
        <div class="top-setting">
          <svg width="31" height="30" viewBox="0 0 31 30" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="0.824585" width="30" height="30" rx="15" fill="#EBF2FF"/>
            <path d="M25.0983 7.571L27.098 10.929C27.2937 11.258 27.3658 11.6425 27.302 12.0172C27.2382 12.3919 27.0424 12.7336 26.7481 12.9842L26.0642 13.5653C25.6418 13.1851 25.1802 12.8453 24.6861 12.552L25.6296 11.7504L23.63 8.39243L20.7093 9.35021C20.0305 8.79553 19.258 8.35868 18.4258 8.05893L17.8242 5.14286H13.8249L13.2234 8.05893C12.3851 8.35444 11.6065 8.78978 10.9229 9.34529L8.0192 8.39243L6.01956 11.7504L8.32254 13.7128C8.1685 14.563 8.1705 15.4328 8.32847 16.2823L6.01956 18.2496L8.0192 21.6076L10.9399 20.6498C11.1534 20.8243 11.3762 20.9871 11.6072 21.1377C11.9876 23.3289 13.2419 25.2325 15.0107 26.5H13.8249C13.433 26.5002 13.0532 26.3686 12.7501 26.1278C12.447 25.8869 12.2393 25.5517 12.1625 25.1791L11.7363 23.1108C11.3514 22.9281 10.98 22.7197 10.6247 22.4873L8.56233 23.1642C8.19109 23.2864 7.78761 23.2799 7.42076 23.1458C7.05391 23.0118 6.74644 22.7584 6.55082 22.429L4.55118 19.071C4.35549 18.742 4.28341 18.3575 4.34721 17.9828C4.41101 17.6081 4.60675 17.2664 4.90112 17.0158L6.52795 15.6292C6.51269 15.4214 6.50422 15.2119 6.50422 15C6.50422 14.8246 6.5167 14.652 6.52922 14.4789L6.53642 14.3782L4.90027 12.9842C4.60617 12.7334 4.41077 12.3916 4.34728 12.0169C4.28379 11.6423 4.35614 11.2578 4.55203 10.929L6.55167 7.571C6.74735 7.24211 7.0546 6.98917 7.42107 6.85527C7.78754 6.72137 8.19056 6.71478 8.56148 6.83664L10.612 7.50857C10.9715 7.27734 11.3472 7.07066 11.7363 6.89004L12.1625 4.82086C12.2393 4.44829 12.447 4.11306 12.7501 3.87222C13.0532 3.63139 13.433 3.49985 13.8249 3.5H17.8242C18.2161 3.49985 18.596 3.63139 18.8991 3.87222C19.2022 4.11306 19.4098 4.44829 19.4866 4.82086L19.9128 6.89004C20.2977 7.07266 20.6691 7.2807 21.0245 7.51268L23.0868 6.83664C23.458 6.71436 23.8614 6.72072 24.2282 6.85464C24.5951 6.98857 24.9026 7.24176 25.0983 7.571Z" fill="#2F76FF"/>
            <path d="M19.258 11.3652C18.8233 10.9793 18.3204 10.6676 17.7701 10.4466C16.8412 10.0736 15.819 9.97596 14.8328 10.1661C13.8467 10.3563 12.9408 10.8257 12.2298 11.515C11.5188 12.2042 11.0347 13.0824 10.8385 14.0385C10.6423 14.9945 10.743 15.9855 11.1278 16.8861C11.2785 17.2388 11.4701 17.5714 11.6977 17.8782C11.8712 17.1301 12.1476 16.4197 12.5116 15.7617C12.4551 15.5123 12.4294 15.2566 12.4354 15C12.4252 14.5658 12.5059 14.1341 12.6726 13.731C12.8394 13.3279 13.0886 12.9617 13.4054 12.6546C13.7222 12.3475 14.0999 12.1059 14.5157 11.9443C14.9315 11.7826 15.3768 11.7044 15.8246 11.7143C16.2253 11.7054 16.6239 11.7671 17.0012 11.8959C17.7125 11.626 18.4696 11.4444 19.258 11.3652Z" fill="#2F76FF"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M20.3246 26.8999C24.1906 26.8999 27.3246 23.7659 27.3246 19.8999C27.3246 16.0339 24.1906 12.8999 20.3246 12.8999C16.4586 12.8999 13.3246 16.0339 13.3246 19.8999C13.3246 23.7659 16.4586 26.8999 20.3246 26.8999ZM14.7938 18.4182C14.6683 18.8892 14.6014 19.3841 14.6014 19.8947C14.6014 20.4052 14.6683 20.9001 14.7938 21.3711H16.989C16.9335 20.9024 16.9018 20.4094 16.9018 19.8947C16.9018 19.3799 16.9335 18.887 16.989 18.4182H14.7938ZM15.508 16.8036H17.2872C17.4751 16.0592 17.711 15.4065 17.9467 14.8604C17.9779 14.7882 18.0091 14.7177 18.0402 14.6491C16.998 15.1025 16.1172 15.8574 15.508 16.8036ZM20.1153 14.1805C20.0951 14.2127 20.0737 14.2474 20.0511 14.2846C19.884 14.5603 19.6571 14.9719 19.429 15.5003C19.2657 15.8787 19.1024 16.3154 18.9601 16.8036H21.6781C21.5358 16.3154 21.3725 15.8787 21.2092 15.5003C20.9811 14.9719 20.7541 14.5603 20.5871 14.2846C20.5645 14.2474 20.5431 14.2127 20.5229 14.1805C20.4552 14.1782 20.3873 14.177 20.3191 14.177C20.2509 14.177 20.1829 14.1782 20.1153 14.1805ZM22.598 14.6491C22.6291 14.7177 22.6603 14.7882 22.6915 14.8604C22.9272 15.4065 23.1631 16.0592 23.3509 16.8036H25.1301C24.5209 15.8574 23.6402 15.1025 22.598 14.6491ZM25.8444 18.4182H23.6492C23.7047 18.887 23.7364 19.3799 23.7364 19.8947C23.7364 20.4094 23.7047 20.9024 23.6492 21.3711H25.8444C25.9699 20.9001 26.0368 20.4052 26.0368 19.8947C26.0368 19.3841 25.9699 18.8892 25.8444 18.4182ZM25.1301 22.9857H23.3509C23.1631 23.7301 22.9272 24.3829 22.6915 24.9289C22.6603 25.0012 22.6291 25.0716 22.598 25.1402C23.6402 24.6868 24.5209 23.932 25.1301 22.9857ZM20.5229 25.6088C20.5431 25.5767 20.5645 25.5419 20.5871 25.5047C20.7541 25.2291 20.9811 24.8174 21.2092 24.289C21.3725 23.9106 21.5358 23.4739 21.6781 22.9857H18.9601C19.1024 23.4739 19.2657 23.9106 19.429 24.289C19.6571 24.8174 19.884 25.2291 20.0511 25.5047C20.0737 25.5419 20.0951 25.5767 20.1153 25.6088C20.1829 25.6112 20.2509 25.6124 20.3191 25.6124C20.3873 25.6124 20.4552 25.6112 20.5229 25.6088ZM18.0402 25.1402C18.0091 25.0716 17.9779 25.0012 17.9467 24.9289C17.711 24.3829 17.4751 23.7301 17.2872 22.9857H15.508C16.1172 23.932 16.998 24.6868 18.0402 25.1402ZM22.0217 21.3711C22.0849 20.9062 22.1218 20.4129 22.1218 19.8947C22.1218 19.3764 22.0849 18.8831 22.0217 18.4182H18.6165C18.5532 18.8831 18.5164 19.3764 18.5164 19.8947C18.5164 20.4129 18.5532 20.9062 18.6165 21.3711H22.0217Z" fill="#2F76FF"/>
          </svg>
          <div class="setting-admin">
            <svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M10.8246 20C8.45681 20 6.16029 19.1577 4.35806 17.6281C3.9349 17.2692 3.53794 16.8713 3.17833 16.4455C1.66041 14.6462 0.824585 12.3573 0.824585 10C0.824585 7.32887 1.86474 4.81766 3.75349 2.92891C5.64224 1.04016 8.15345 0 10.8246 0C13.4957 0 16.0069 1.04016 17.8957 2.92891C19.7844 4.81766 20.8246 7.32887 20.8246 10C20.8246 12.3573 19.9888 14.6463 18.471 16.4452C18.1112 16.8713 17.7143 17.2692 17.291 17.6282C15.4889 19.1577 13.1924 20 10.8246 20ZM10.8246 1.25C5.99982 1.25 2.07458 5.17523 2.07458 10C2.07458 12.0627 2.8058 14.0654 4.13353 15.6392C4.44837 16.012 4.79607 16.3605 5.16677 16.675C6.74349 18.0131 8.75275 18.75 10.8246 18.75C12.8964 18.75 14.9057 18.0131 16.4823 16.675C16.8531 16.3605 17.2008 16.0119 17.5158 15.6389C18.8434 14.0654 19.5746 12.0627 19.5746 10C19.5746 5.17523 15.6494 1.25 10.8246 1.25Z" fill="#2F76FF"/>
              <path d="M10.8246 10C8.75681 10 7.07458 8.31777 7.07458 6.25C7.07458 4.18223 8.75681 2.5 10.8246 2.5C12.8924 2.5 14.5746 4.18223 14.5746 6.25C14.5746 8.31777 12.8924 10 10.8246 10ZM10.8246 3.75C9.44607 3.75 8.32458 4.87148 8.32458 6.25C8.32458 7.62852 9.44607 8.75 10.8246 8.75C12.2031 8.75 13.3246 7.62852 13.3246 6.25C13.3246 4.87148 12.2031 3.75 10.8246 3.75Z" fill="#2F76FF"/>
              <path d="M16.8872 17.7767C16.8368 17.7767 16.7856 17.7706 16.7345 17.7578C16.3997 17.6737 16.1965 17.3342 16.2805 16.9994C16.3927 16.5524 16.4496 16.09 16.4496 15.625C16.4496 12.567 13.9634 10.0443 10.9069 10.0004L10.8246 10L10.7423 10.0004C7.68576 10.0443 5.19958 12.567 5.19958 15.625C5.19958 16.09 5.2565 16.5524 5.36869 16.9994C5.45271 17.3342 5.24943 17.6737 4.91466 17.7578C4.5799 17.8418 4.24033 17.6386 4.1563 17.3038C4.01912 16.7573 3.94958 16.1925 3.94958 15.625C3.94958 13.8055 4.65337 12.0905 5.9313 10.7957C7.20798 9.50219 8.91119 8.77586 10.7272 8.75047C10.7301 8.75043 10.733 8.75043 10.7359 8.75043L10.8246 8.75L10.9133 8.75039C10.9162 8.75039 10.9191 8.75039 10.922 8.75043C12.738 8.77578 14.4412 9.50215 15.7179 10.7957C16.9958 12.0905 17.6996 13.8055 17.6996 15.625C17.6996 16.1925 17.6301 16.7573 17.4929 17.3038C17.4217 17.5874 17.167 17.7767 16.8872 17.7767Z" fill="#2F76FF"/>
            </svg>
            <span>Log in</span>
          </div>
        </div>
        <ul class="nav-list">
          <li class="nav-item">
            <div>
              <select name="" id="">
                <option value=""><img src="" alt=""> Sell at Turk</option>
                <option value="">Lorem</option>
                <option value="">Lorem</option>
              </select>
            </div>
          </li>
          <div class="top-border"></div>
          <li class="nav-item">
            <div>
              <select name="" id="">
                <option value=""><img src="" alt=""> Help</option>
                <option value="">Setting</option>
                <option value="">FAQ</option>
              </select>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Mobile app</a>
          </li>
          <div class="top-border"></div>
          <li class="nav-item">
            <div class="dropdown-currency">
              <select class="dropdown-select" name="" id="">
                <option value="">$ USD</option>
                <option value="">TRY</option>
                <option value="">RUB</option>
              </select>
            </div>
          </li>
          <li class="nav-item">
            <div>
              <img src="@/assets/flag.png" alt="">
              <select name="" id="">
                <option value=""> English</option>
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
  width: 150px;
  height: 30px;
}

.header .header-wrapper .top-nav .top-logo img {
  width: 100%;
}

.header .header-wrapper .top-nav .top-setting {
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
  width: 98px;
}

.header .header-wrapper .top-nav .nav-list .nav-item div {
  display: flex;
}

.header .header-wrapper .top-nav .nav-list .top-border {
  width: 13px;
  border: 1px solid #CDCDCD;
  transform: rotate(90deg);
}

.header .header-wrapper .top-nav .nav-list .nav-item select {
  border: none;
  background: #fafafa;
}

.header .header-wrapper .top-nav .nav-list .nav-item select:last-child {
  margin-left: 5px;
}

.header .header-wrapper .top-nav .nav-list .nav-item select:last-child div img {
  image-rendering: -webkit-optimize-contrast;
}

.header .header-wrapper .top-nav .nav-list .nav-item .nav-link {
  text-decoration: none;
  color: #0A0A0A;
  font-weight: 300px;
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
  max-width: 640px;
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
    width: 290px;
    justify-content: space-between;
    margin: auto;
  }

  .header .header-wrapper .top-nav .top-logo {
    display: block;
    width: 150px;
    height: 30px;
  }

  .header .header-wrapper .top-nav .top-logo img {
    image-rendering: -webkit-optimize-contrast;
  }

  .header .header-wrapper .top-nav .top-setting {
    display: flex;
    justify-content: space-between;
    width: 108px;
  }

  .header .header-wrapper .top-nav .top-setting .setting-admin {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    width: 73px;
    height: 30px;
    background: #EBF2FF;
    border-radius: 5px;
  }

  .header .header-wrapper .top-nav .top-setting .setting-admin span {
    font-size: 14px;
    color: #2F76FF;
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
    width: 82%;
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

@media only screen and (min-width: 375px) {
  .header .header-wrapper .top-nav {
    width: 320px;
  }

  .header .header-wrapper .header__main .header__search {
    width: 320px;
  }
}

@media only screen and (min-width: 414px) {
  .header .header-wrapper .top-nav {
    width: 370px;
  }

  .header .header-wrapper .header__main .header__search {
    width: 370px;
  }
}

@media only screen and (min-width: 768px) {
  .header .header-wrapper .top-nav {
    width: 700px;
    justify-content: space-between;
  }

  .header .header-wrapper .top-nav .top-setting {
    display: none;
  }

  .header .header-wrapper .top-nav .nav-list {
    display: flex;
  }

  .header .header-wrapper .header__main {
    align-items: end;
  }

  .header .header-wrapper .header__main .header__button {
    margin-left: 0;
    display: block;
    width: 50px;
  }

  .header .header-wrapper .header__main .header__search {
    margin-left: 10px;
  }

  .header .header-wrapper .admin {
    display: flex;
    width: 195px;
  }

  .header .header-wrapper .admin .admin-list {
    display: flex;
    width: 100%;
    justify-content: space-between;
  }
}

@media only screen and (min-width: 1024px) {
  .header .header-wrapper .top-nav {
    width: 900px;
    justify-content: end;
  }
  .header .header-wrapper .top-nav .top-logo {
    display: none;
  }
  .header .header-wrapper .top-nav .nav-list {
    width: 511px;
  }
  .header .header-wrapper .header__main {
    align-items: center;
  }
  .header .header-wrapper .header__main .header__logo {
    display: block;
  }
  .header .header-wrapper .header__main .header__button {
    width: 60px;
  }
  .header .header-wrapper .header__main .header__search {
    padding-top: 0;
  }
  .header .header-wrapper .header__main .admin {
    margin-left: 10px;
  }
}

@media only screen and (min-width: 1440px) {
  .header {
    height: 110px;
  }

  .header .header-wrapper {
    padding-left: 78px;
    padding-right: 78px;
  }

  .header .header-wrapper .top-nav {
    width: 100%;
  }

  .header .header-wrapper .top-nav .nav-list {
    justify-content: space-between;
  }

  .header .header-wrapper .header__main {
    margin-top: 14px;
    justify-content: center;
  }

  .header .header-wrapper .header__main .header__button {
    margin-left: 15px;
    width: 75px;
  }

  .header .header-wrapper .header__main .header__search {
    margin-left: 15px;
    width: 100%;
  }

  .header .header-wrapper .header__search .btn-search {
    justify-content: unset;
    width: 98px;
  }

  .header .header-wrapper .header__search .btn-search span {
    display: block;
  }

  .header .header-wrapper .header__main .admin {
    width: 287px;
    margin-left: 33px;
  }

  .header .header-wrapper .header__main .admin .admin-list {
    width: 100%;
    justify-content: space-between;
  }
}
</style>
