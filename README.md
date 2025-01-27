<section class="contact-container container">
         <section class="left-contact">
          <h2>Contact Us</h2>
           <section class="left-contact-container" style="margin: 0;">
          </section>
          <section class="right-contact-container">
            <div class="icon" style="margin: 0;">
              <span class="fa-brands fa-whatsapp"></span>
              <span class="fa-brands fa-x-twitter"></span>
              <span class="fa-brands fa-github"></span>
              <span class="fa-brands fa-youtube"></span>
            
            </div>
            <div class="contact" style="margin: 0;">
              <p class="info-contact"><span class="fa-brands fa-whatsapp"> +234 905 816 1216 </span></p>
              <p class="info-tel"><span class="fa-solid fa-phone">  09124138728 </span></p>
            </div>
          </section>
         </section>
          </section>




          .contact-container h2 {
  margin-top: 5rem;
  margin-left: 25rem;
  font-size: 80px;
}
.left-contact-container {
  flex: 3;
}
.left-contact-container {
  cursor: pointer;
}
.left-contact-container:hover {
  animation: bounce 1s infinite;
}
.right-contact-container {
  /* flex: 4; */
  margin-top: 2rem;
  display: flex;
  gap: 25rem;
  font-size: 25px;
  cursor: pointer;
}
.contact {
  display: flex;
  gap: 3rem;
  color: #ffffff;
  cursor: pointer;
  font-size: 25px;
  margin-right: 9rem;
}
.info-contact {
  gap: 1rem;
}
.bounce {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: red;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}
@keyframes bounce {
  0%,
  100% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-20px);
  }
}
.bounce {
  animation: bounce 1s infinite;
}
.fa-brands {
  cursor: pointer;
  font-size: 25px;
}
.fa-brands:hover {
  animation: icons 1s infinite;
}
.fa-solid:hover {
  animation: icons 1s infinite;
}
@keyframes icons {
  0%,
  100% {
    transform: translateY();
  }
  50% {
    transform: translateY(-20px);
  }
}