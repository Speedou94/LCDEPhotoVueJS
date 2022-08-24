<template>
  <section class="main" id="Biographie">
    <div class="content">
      <div class="card">
        <div class="left">
          <h1>Biographie</h1>
          <br />
          <p>
            Je me présente, Ju B. Je suis passionnée par la photographie et les
            animaux.
          </p>
          <p>
            Mes differents shootings photo montre mon amour pour les animaux et
            plus particulièrement les chiens.
          </p>
          <p>
            Je m'exerce également dans les portraits d'enfants et de familles.
          </p>
        </div>
        <div class="right"><img alt="Ju" src="../assets/img/Ju.png" /></div>
      </div>
      <div class="card" id="Materiel">
        <div class="left">
          <h1>Mon materiel</h1>
          <br />
          <p>
            Non loin d'être équipée comme une professionnelle, je possède toute
            fois un setup optimal à tous mes besoins.
          </p>
          <p>
            Mon fidèle Canon Eos 80D est accompagné par un EFS 15-85mm et un
            EF50mm.
          </p>
          <p>
            Je est capable d'immortaliser chaques moments de votre vie peut
            importe la situation et les conditions.
          </p>
        </div>
        <div class="right"><img alt="80D" src="../assets/img/E80D.jpg" /></div>
      </div>
      <div class="card" id="Book">
        <div class="left">
          <h1>Mon Book</h1>
          <br />
          <p>Vous retrouverez ici quelques uns de mes shootings.</p>
          <p>
            Que ce soit en famille, avec des animaux ou encore des portraits de
            véhicules en tout genres.
          </p>
          <p>
            Je vous laisse découvrir tout cela au travers des shooting que vous
            trouverez dans mon book.
          </p>
        </div>
        <div class="right"><img alt="A" src="../assets/img/Sam8.jpg" /></div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
.main {
  margin-top: 5rem;
  margin-bottom: 10rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.main .content .card {
  margin-top: 5rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin-bottom: 20px;
}
.main .content .card .left {
  flex: 100 0 30%;
  padding: 20px;

  background-color: rgb(170, 137, 77);
  font-size: 24px;
  font-family: "Ramaraja", serif;
  color: #ffffff;
}
.main .content .card.right {
  flex: 0 0 70%;
}
.main .content .card .right img {
  height: 500px;
  width: 500px;
  margin-top: 5px;
}
</style>

<script>
export default {
  name: "Cartes",
  props: {
    msg: String,
  },
};
</script>
