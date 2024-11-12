https://github.com/diasmxm/ono-tebe-nado



.lots {
  /* display: inline-block;
  width: 1100px; */
  /* padding: 179px 25px 146px; */
  padding: 0 50px;
  
}

.lots__heading {
  display: inline-block;
  padding-left: 14px;
  font-weight: bold;
  font-size: 40px;
  text-transform: uppercase;

  /* padding: 0 0 30px 40px;
  font-weight: bold;
  font-size: 40px;
  line-height: 1;
  text-transform: uppercase; */
}

.lots__card-list {
  display: grid;
  grid-template-columns: repeat(3, 334px);
  grid-template-rows: 563px;
  justify-content: space-around;
  gap: 25px;
  padding-top: 25px;
  list-style: none;
  margin-bottom: 30px;
  
}

.lost__card-list-item {
  height: 100%;
}

.card-link {
  display: block;
  height: 100%;
  text-decoration: none;
  
}

.card {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  position: relative;
  gap: 30px;
  width: auto;
  /* height: 100%; */
  min-height: 563px;
  padding: 50px 40px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  
}

.card_type_film {
  background-image: url(../images/card-lot-01.jpg);
}

.card_type_book {
  background-image: url(../images/card-lot-02.jpg);
}

.card_type_picture {
  background-image: url(../images/card-lot-03.jpg);
}

.card__title {
  position: relative;
  z-index: 1;
  color: #FFF;
  font-weight: bold;
  font-size: 22px;
  /* line-height: 1.2; */
  text-decoration-line: underline;
  text-transform: uppercase;
}

.card__text {
  /* position: relative;
  z-index: 1;
  color: #FFF;
  font-size: 20px;
  line-height: 1.2; */

  z-index: 1;
  align-self: center;
  width: 254px;
  padding-bottom: 49px;
  color: #fff;
  font-weight: 400;
  font-size: 20px;
  line-height: 24px;
}

.lots__look-more-link {
  /* display: block;
  margin: 30px 0 0 40px;
  font-size: 20px;
  text-decoration-line: underline;
  text-underline-position: under;
  width: fit-content; */

  width: 1052px;
  padding-left: 40px; /* По РЕВЬЮ */
  color: #000;
  font-weight: 400;
  font-size: 20px;
  text-decoration: underline;
}