<template>
  <div>

    <JumboHero />

    <b-card
      img-src="https://placekitten.com/300/300"
      img-alt="Card image"
      title="Card Title"
      img-right
    >
      <b-card-text>Some quick example text to build on the card and make up the bulk of the card's content.</b-card-text>
    </b-card>

    <ElementHeader />
    <FeaturesCards />
  </div>
</template>

<script>
import JumboHero from "@/components/JumboHero";
import ElementHeader from "@/components/ElementHeader";
import FeaturesCards from "@/components/FeaturesCards";

export default {
  components: {
    JumboHero,
    ElementHeader,
    FeaturesCards
  }
};
</script>

<style>
</style>
