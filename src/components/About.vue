<template>
  <div id="about">
    <div>
      <h1>About suvat</h1>
      <p>Suvat is first and foremost acronym.</p>
      <p>s = displacement</p>
      <p>u = initial velocity</p>
      <p>v = final velocity</p>
      <p>a = acceleration</p>
      <p>t = time</p>
      <p>These variables are linked by the suvat equations.</p>
      <Mathr
        formula="$v=u+at\\s=ut+\frac{1}{2}at^2\\s=\frac{1}{2}(u+v)t\\v^2=u^2+2as\\s=vt-\frac{1}{2}at^2$"
      />
      <p>
        Using these equations any three variables combined with the correct
        equations can be used to calcuate the other two values.
      </p>
    </div>
  </div>
</template>

<script>
import Mathr from "./Mathr.vue";
export default {
  name: "About",
  components: {
    Mathr
  }
};
</script>

<style scoped lang="sass">

#about
  display: flex
  justify-content: center
  text-align: left
  div
    width: 90%
    @media (min-width: 820px)
      width: 800px
    p
      font-size: 1.1em
</style>