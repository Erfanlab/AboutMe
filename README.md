<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
/><style>
  article {
    color: white;
    width: 865px;
    height: 923px;
    background-color: #555555;
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 50px;
    > div {
      width: 865px;
      height: 92px;
      background-color: #787878;
    }
    header {
      width: 865px;
      height: 285px;
      background-color: #787878;
      display: flex;
    }
    h1 {
      width: 393.81px;
      height: 68.21px;
      background-color: #787878;
      border-radius: 5px;
      display: flex;
      gap: 10px;
      text-align: center;
      justify-content: center;
      align-items: center;
      font-family: sans-serif;
      transition: all 0.2s ease-in-out;
      &:hover {
        transition: all 0.2s ease-in-out;
        background-color: #298096;
      }
    }
    .languages {
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: row !important;
      justify-content: center;
      align-items: center !important;
      flex-wrap: wrap;
      gap: 20px;
    }
    main {
      width: 80%;
      display: flex;
      align-items: center;
      gap: 50px;
      font-family: sans-serif;
      margin-left: 50px;
      margin-right: 50px;
      div {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: left;
        p {
          width: 100%;
          text-align: left;
          color: white;
          font-size: large;
          font-weight: bold;
        }
        .card {
          width: 100%;
          height: 220.53px;
          background-color: #787878;
          display: flex;
          justify-content: center;
          align-items: start;

          border-radius: 5px;
          form {
            width: 100%;
            height: 100%;
            font-size: 13px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-self: center;
            margin: 20px 0 0 0;
            p {
              width: 100%;
              text-align: center;
            }
            input {
              border-radius: 5px;
            }
            a {
              font-size: 11px;
              color: white;
              font-size: 15px;
              font-weight: bold;
              button {
                width: 100px;
                height: 30px;
                border-radius: 5px;
                background-color: #0e8f53;
                color: white;
              }
            }
            .allbtn {
              margin-top: 10px;
              display: flex;
              flex-direction: row;
              gap: 5px;
              width: 100%;
              .btn-primary {
                background-color: #298096;
                width: 80px;
                height: 20px;
                color: white;
              }
            }
          }
        }
      }
    }
    footer {
      width: 500px;
      height: 50px;
      background-color: #787878;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: space-around;
      gap: 10px;

      div {
        width: 10%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        a {
          width: 100%;
          height: 100%;
          font-size: 40px;
          display: flex;
          justify-content: center;
          align-items: center;
          text-decoration: none;
          .fa {
            display: flex;
            justify-content: center;
            align-items: center;
          }
          i {
            width: 100%;
            height: 100%;
            color: white;
          }
        }
      }
    }
  }
</style>

<article>
  <header></header>
  <h1>
    <li class="fa fa-user"></li>
    <p>MohammadErfan Labbafi</p>
  </h1>
  <main>
    <div>
      <p>Languages & Frameworks:</p>
      <div class="card languages">
        <img
          width="40"
          height="40"
          src="https://s32.picofile.com/file/8478593326/javascript.png"
          alt="javascript"
        />
        <img
          width="40"
          height="40"
          src="https://s32.picofile.com/file/8478600426/typescript.png"
          alt="TypeScript"
        />
        <img
          width="40"
          height="40"
          src="https://s32.picofile.com/file/8478593376/sass.png"
          alt="sass"
        />
        <img
          width="40"
          height="40"
          src="https://s32.picofile.com/file/8478593384/tailwind.png"
          alt="tailwind"
        />
        <img
          width="40"
          height="40"
          src="https://s32.picofile.com/file/8478593334/html.png"
          alt="html"
        />
        <img
          width="40"
          height="40"
          src="https://s32.picofile.com/file/8478600476/css.png"
          alt="css"
        />
        <img
          width="40"
          height="40"
          src="https://s32.picofile.com/file/8478600442/giticon.png"
          alt="git"
        />
      </div>
    </div>
    <div>
      <p>Send Email:</p>
      <div class="card">
        <form
          style="color: white"
          action="mailto:erfanlab2000@gmail.com"
          method="post"
          enctype="text/plain"
        >
          Your Name:<br />
          <input class="c-name" type="text" name="name" size="30" />
          Email:
          <input class="c-name" type="text" name="mail" size="30" />
          Text:

          <input class="c-text" type="text" name="comment" size="30" />
          <div class="allbtn">
            <input
              class="btn btn-primary"
              id="liveAlertBtn"
              type="submit"
              value="Send"
            />
            <input
              class="btn btn-primary"
              id="liveAlertBtn-1"
              type="reset"
              value="Claer"
            />
          </div>
          <p>
            <a class="phone" href="tel:+989919295106">
              <button>CallMe...</button>
            </a>
          </p>
        </form>
      </div>
    </div>
  </main>
  <footer>
    <div>
      <a href="">
        <i class="fa fa-instagram"></i>
      </a>
    </div>
    <div>
      <a href="https://t.me/Erfan_MFD">
        <i class="fa fa-telegram"></i>
      </a>
    </div>
    <div>
      <a href="https://github.com/Erfanlab">
        <i class="fa fa-github"></i>
      </a>
    </div>
    <div>
      <a href="https://www.linkedin.com/in/mohammaderfan-labbafi-2b300b22a/">
        <i class="fa fa-linkedin"></i>
      </a>
    </div>
  </footer>
</article>
