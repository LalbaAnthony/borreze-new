<template>
  <h2 class="page-title">Salle des fêtes</h2>
  <section>
    <img class="page-img" src="/public/photos/borreze-scene_sdf.webp" alt="Photo de la salle des fêtes de Borrèze">
  </section>
  <section>
    <h3 class="section-title">Spécificités:</h3>
    <p>La salle a une superficie totale de 360 m² et comprend:</p>
    <ul class="fancy-list">
      <li>Une entrée de 37 m²</li>
      <li>Une scène de 60 m²</li>
      <li>Un bar de 17 m²</li>
      <li>Une réserve de 12 m²</li>
      <li>Un bloc Sanitaire de 17 m²</li>
    </ul>
    <br>
    <p>Avec:</p>
    <ul class="fancy-list">
      <li>La salle est équipée pour réussir votre manifestation</li>
      <li>240 chaises</li>
      <li>40 tables de 1.80m</li>
      <li>Un écran de 3m x 2.4m</li>
      <li>Un projecteur fixé au plafond</li>
      <li>Quatre projecteurs télécommandés sur rampe</li>
      <li>Un tableau électrique spécial traiteur</li>
    </ul>
    <br>
    <p>
      La salle répond aux normes en vigueur pour l'accueil des enfants et des personnes en situation de handicap.
    </p>
    <br>
    <p>
      La salle des fêtes est située <a class="link"
        href="https://www.google.fr/maps/place/44%C2%B057'10.2%22N+1%C2%B023'14.4%22E/@44.9527622,1.3871338,44m"
        target="_blank" rel="noopener noreferrer">
        à proximité de l'école</a>.
    </p>
  </section>
  <section>
    <h3 class="section-title">Réservations:</h3>
    <p>
      Elle est disponible à la location pour les particuliers, les associations
      et les entreprises.
    </p>
    <p>
      Pour toute demande de location, merci de contacter la mairie au
      <a class="link" href="tel:+33553288338">05 53 28 83 38</a>, ou par mail à <a class="link"
        href="mailto:mairie.borreze@wanadoo.fr">mairie.borreze@wanadoo.fr</a>.
    </p>
  </section>
  <section>
    <h3 class="section-title">Tarifs:</h3>
    <table>
      <thead>
        <tr>
          <th rowspan="2">&nbsp;</th>
          <th rowspan="2">Caution salle</th>
          <th rowspan="2">Caution ménage</th>
          <th colspan="2">Tarifs Location</th>
        </tr>
        <tr>
          <th>Été ☀️</th>
          <th>Hiver ❄️</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>Borrèziens</th>
          <td>500.00 €</td>
          <td>160.00 €</td>
          <td>150.00 €</td>
          <td>200.00 €</td>
        </tr>
        <tr>
          <th>Non Borrèziens</th>
          <td>500.00 €</td>
          <td>160.00 €</td>
          <td>350.00 €</td>
          <td>400.00 €</td>
        </tr>
        <tr>
          <th>Associtations</th>
          <td>500.00 €</td>
          <td>160.00 €</td>
          <td>Gratuit</td>
          <td>Gratuit</td>
        </tr>
      </tbody>
    </table>
  </section>
</template>

<script setup>
</script>

<style scoped>
table {
  width: 100%;
  border-collapse: collapse;
}

thead {
  background-color: var(--primary);
  color: var(--light);
}

table,
th,
td {
  border: 1px solid black;
}

th,
td {
  text-align: center;
}

td {
  padding: 0.5rem 0.25rem;
}

td.primary {
  background-color: var(--primary);
  color: var(--light);
}
</style>
