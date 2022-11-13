<template>
  <div id="sobre" class="sobre">
    <section id="pricing" class="pricing-area">
      <div class="container">
        <center>
          <div class="card-body">
            <h2>Sobre Nós</h2>
            <p class="card-text">
              Muito prazer, Natália ou como eu gosto que me chamem: Naty. O
              rosto por trás da Hera eventos. Tenho 30 anos, sou casada e amo
              realizar sonhos. Sempre tive um amor diferente pelo mundo dos
              casamentos, então fiz um curso para aprender sobre a área e ver se
              eu gostava mesmo. ME APAIXONEI e tive a certeza de que era essa a
              minha profissão. Comecei na área com a oportunidade que uma
              assessora de alto renome no mercado me deu, onde fui estagiária,
              assistente e coordenadora e foi uma escola. Depois disso, consegui
              realizar o sonho de trabalhar no Grupo Bisutti sendo produtora de
              execução por onde fiquei por dois anos e também desempenhei
              funções na área do corporativo. Após isso voltei para o grupo da
              primeira assessora que trabalhei e virei sócia na sua segunda
              marca. Com toda essa história, tenho mais de 340 eventos
              realizados entre casamentos, aniversários, bodas, debutante e
              corporativos. Em todos esses anos percebi a dificuldade que muitos
              noivos tinham no processo de planejamento por não ter uma pessoa
              focada ou por essa pessoa não ter o conhecimento necessário para
              seguir com todas as nuances que permeia o processo do casamento,
              além de não inspirar os noivos a trazer sua personalidade para o
              casamento, para mudar isso comecei a minha própria empresa de
              eventos, a Hera Eventos, onde presença, acompanhamento,
              experiência e orientação é o nosso foco.
            </p>
          </div>
        </center>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.color-1 {
  fill: #945d41;
  isolation: isolate;
}
.cls-1 {
  opacity: 0.1;
}
.cls-2 {
  opacity: 0.2;
}
.cls-3 {
  opacity: 0.4;
}
.cls-4 {
  opacity: 0.6;
}
.color-2 {
  fill: #ccc;
  isolation: isolate;
}
.cls-1 {
  opacity: 0.1;
}
.cls-2 {
  opacity: 0.2;
}
.cls-3 {
  opacity: 0.4;
}
.cls-4 {
  opacity: 0.6;
}
.color-3 {
  fill: #e5c645;
  isolation: isolate;
}
.cls-1 {
  opacity: 0.1;
}
.cls-2 {
  opacity: 0.2;
}
.cls-3 {
  opacity: 0.4;
}
.cls-4 {
  opacity: 0.6;
}
/*===========================
      4.PRICING css 
===========================*/
.pricing-area {
  padding-top: 120px;
  padding-bottom: 120px;
  background-color: #f4f6f7;
  font-family: "Alice", serif;
}
@media only screen and (min-width: 768px) and (max-width: 991px) {
  .pricing-area {
    padding-top: 100px;
    padding-bottom: 100px;
  }
}
@media (max-width: 767px) {
  .pricing-area {
    padding-top: 80px;
    padding-bottom: 80px;
  }
}

.single-pricing {
  -webkit-box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.16);
  -moz-box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.16);
  box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.16);
  padding: 24px 20px 50px;
  border-radius: 8px;
  position: relative;
  overflow: hidden;
  background-color: #fff;
}
.single-pricing .pricing-header .sub-title {
  font-size: 20px;
  font-weight: 600;
  line-height: 25px;
  color: #121212;
  position: relative;
  padding-bottom: 8px;
}
.single-pricing .pricing-header .sub-title::before {
  position: absolute;
  content: "";
  width: 72px;
  height: 4px;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: #945d41;
  margin: 0 auto;
}
.single-pricing .pricing-header .price {
  display: block;
  font-size: 50px;
  font-weight: 600;
  line-height: 80px;
  margin-top: 32px;
  color: #121212;
}
@media only screen and (min-width: 992px) and (max-width: 1200px) {
  .single-pricing .pricing-header .price {
    font-size: 50px;
    margin-top: 16px;
  }
}
@media (max-width: 767px) {
  .single-pricing .pricing-header .price {
    font-size: 50px;
    margin-top: 16px;
  }
}
@media only screen and (min-width: 576px) and (max-width: 767px) {
  .single-pricing .pricing-header .price {
    font-size: 64px;
    margin-top: 32px;
  }
}
.single-pricing .pricing-header .year {
  font-size: 20px;
  font-weight: 500;
  line-height: 25px;
  color: #6c6c6c;
  margin-top: 3px;
}
.single-pricing .pricing-list {
  margin-top: 40px;
  margin-bottom: 35px;
}

.single-pricing .pricing-list ul li {
  font-size: 16px;
  line-height: 24px;
  color: #121212;
  margin-top: 16px;
}
@media only screen and (min-width: 992px) and (max-width: 1200px) {
  .single-pricing .pricing-list ul li {
    font-size: 14px;
    margin-top: 12px;
  }
}
@media (max-width: 767px) {
  .single-pricing .pricing-list ul li {
    font-size: 14px;
    margin-top: 12px;
  }
}
@media only screen and (min-width: 576px) and (max-width: 767px) {
  .single-pricing .pricing-list ul li {
    font-size: 16px;
    margin-top: 16px;
  }
}
.single-pricing .pricing-list ul li i {
  color: #0067f4;
  margin-right: 8px;
}
.single-pricing .pricing-btn {
  margin-top: 42px;
}
.single-pricing .pricing-btn .main-btn {
  background-color: #0067f4;
  border-radius: 50px;
  color: #fff;
  border-color: #0067f4;
}
.single-pricing .pricing-btn .main-btn:hover {
  background-color: #005ad5;
  border-color: #005ad5;
}
.single-pricing .buttom-shape {
  position: absolute;
  bottom: -20px;
  left: 0;
  width: 101%;
}

.single-pricing.pro .pricing-header .sub-title::before {
  background-color: #ccc;
  position: absolute;
  content: "";
  width: 72px;
  height: 4px;
  bottom: 0;
  left: 0;
  right: 0;
  margin: 0 auto;
}

.single-pricing.pro .pricing-baloon {
  position: absolute;
  top: 0;
  right: -78px;
  width: 156px;
}

.single-pricing.enterprise .pricing-header .sub-title::before {
  background-color: #e5c645;
  position: absolute;
  content: "";
  width: 72px;
  height: 4px;
  bottom: 0;
  left: 0;
  right: 0;
  margin: 0 auto;
}

.single-pricing.enterprise .pricing-flower {
  position: absolute;
  top: 10px;
  left: 10px;
  width: 144px;
}
@media only screen and (min-width: 992px) and (max-width: 1200px) {
  .single-pricing.enterprise .pricing-flower {
    width: 110px;
  }
}
@media (max-width: 767px) {
  .single-pricing.enterprise .pricing-flower {
    width: 110px;
  }
}
@media only screen and (min-width: 576px) and (max-width: 767px) {
  .single-pricing.enterprise .pricing-flower {
    width: 144px;
  }
}
.single-pricing.enterprise .pricing-flower img {
  width: 100%;
}

/*===========================
    5.CALL TO ACTION css 
===========================*/
.call-to-action {
  background-color: #0067f4;
  position: relative;
}

.call-action-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 50%;
  height: 100%;
}
@media only screen and (min-width: 768px) and (max-width: 991px) {
  .call-action-image {
    position: relative;
    width: 100%;
  }
}
@media (max-width: 767px) {
  .call-action-image {
    position: relative;
    width: 100%;
  }
}
.call-action-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center center;
}

.call-action-content {
  max-width: 560px;
  margin: 0 auto;
  padding-top: 230px;
  padding-bottom: 236px;
}
@media (max-width: 767px) {
  .call-action-content {
    padding-top: 80px;
    padding-bottom: 80px;
  }
}
.call-action-content .call-title {
  font-size: 44px;
  font-weight: 600;
  color: #fff;
  line-height: 55px;
}
@media (max-width: 767px) {
  .call-action-content .call-title {
    font-size: 28px;
    line-height: 38px;
  }
}
.call-action-content .text {
  font-size: 16px;
  color: #fff;
  line-height: 24px;
  margin-top: 16px;
}
@media (max-width: 767px) {
  .call-action-content .text {
    font-size: 14px;
  }
}
.call-action-content .call-newsletter {
  max-width: 410px;
  position: relative;
  margin: 24px auto 0;
}
.call-action-content .call-newsletter i {
  font-size: 26px;
  color: #0067f4;
  position: absolute;
  left: 18px;
  top: 15px;
}
.call-action-content .call-newsletter input {
  width: 100%;
  height: 56px;
  border: 0;
  border-radius: 50px;
  background-color: #fff;
  padding-left: 60px;
  padding-right: 30px;
}
.call-action-content .call-newsletter input::placeholder {
  opacity: 1;
  color: #6c6c6c;
}
.call-action-content .call-newsletter input::-moz-placeholder {
  opacity: 1;
  color: #6c6c6c;
}
.call-action-content .call-newsletter input::-moz-placeholder {
  opacity: 1;
  color: #6c6c6c;
}
.call-action-content .call-newsletter input::-webkit-input-placeholder {
  opacity: 1;
  color: #6c6c6c;
}
.call-action-content .call-newsletter button {
  border: 0;
  border-radius: 50px;
  height: 48px;
  padding: 0 32px;
  font-size: 16px;
  font-weight: 700;
  color: #fff;
  text-transform: uppercase;
  cursor: pointer;
  position: absolute;
  top: 4px;
  right: 4px;
  background-color: #0067f4;
  -webkit-transition: all 0.3s ease-out 0s;
  -moz-transition: all 0.3s ease-out 0s;
  -ms-transition: all 0.3s ease-out 0s;
  -o-transition: all 0.3s ease-out 0s;
  transition: all 0.3s ease-out 0s;
}
@media (max-width: 767px) {
  .call-action-content .call-newsletter button {
    position: relative;
    right: auto;
    margin-top: 15px;
    background-color: #fff;
    color: #0067f4;
  }
}
.call-action-content .call-newsletter button:hover {
  background-color: #005ad5;
  color: #fff;
}
</style>
