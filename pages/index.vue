<template>
  <section class="section">
    <div class="columns is-mobile">
      <div class="column">
        <Modal />
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <Form />
      </div>
    </div>
  </section>
</template>

<script>
import Form from '../components/Form'
import Modal from '../components/Modal'

export default {
  name: 'HomePage',

  components: {
    Modal,
    Form,
  },
}
</script>
