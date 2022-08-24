<template>
  <footer>
    <div class="Footer">
      <h1>Les services</h1>
    </div>
    <div class="services" id="services">
      <div class="contact">
        <h3>Contact</h3>
        <p>
          Une envie de shooting ? Vous pouvez me contacter directement via se
          site, via instagram ou via facebook.
        </p>
      </div>
      <div class="gps">
        <h3>Zone géographique</h3>
        <p>
          J'excerce surtout dans le département de la Vendée et ses alentours
          mais je ne suis pas fermée à d'autres départements si le projet me
          tiens à coeur.
        </p>
      </div>
      <div class="droits">
        <h3>Droits</h3>
        <p>
          Toutes les photos présente sur se site sont soumise à des droits
          d'auteurs, aucune reproduction, partages et ou utilisations sont
          strictement interdite.
        </p>
      </div>
    </div>
    <p id="contact">&copy; Agence Speed&Co' pour Ju' B. 2022</p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  setup() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
footer {
  margin-top: 40px;
  border-top: 5px solid #6f6f6f;
  background-color: rgb(170, 137, 77);
  color: white;
  padding: 30px 100px;
}
footer h1 {
  display: inline-block;
  font-size: 40px;
  font-family: "Ramaraja", serif;
  border-bottom: 1px solid white;
  width: 9%;
  padding-bottom: 0px;
}
.services {
  margin-top: 30px;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: center;
  align-items: baseline;
}
.gps {
  margin-right: 10rem;
  max-width: 300px;
  padding: 10px;
}
.droits {
  margin-bottom: 5rem;
  margin-left: 10rem;
  max-width: 300px;
  padding: 10px;
}
.contact {
  margin-right: 20rem;
  margin-bottom: 2rem;
  max-width: 300px;
  padding: 10px;
}
</style>
