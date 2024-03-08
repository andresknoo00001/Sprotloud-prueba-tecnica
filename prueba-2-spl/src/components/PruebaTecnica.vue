<template>
  <section id="prueba-tecnica">
    <h5 class="title">
      Prueba tecnica Sprotloud representacion basica de formulario html y css
    </h5>
    <section class="formulario">
      <h6>Formulario de conversiones</h6>
      <q-form id="conversion-form">
        <div class="conversion-field">
          <label for="#term-conversion">Conversion term</label>
          <q-input
            requiered
            id="term-conversion"
            rounded
            outlined
            v-model="text"
            label="Term conversion"
          />
        </div>
        <div class="description-field">
          <textarea name="description" id="descrition" rows="10"></textarea>
        </div>
      </q-form>
    </section>
    <section id="condicionales">
      <h6>Conditions</h6>
      <hr>
      <div class="conditions-group-general-container">
        <div class="row1 row justify-center space-between">
          <q-select rounded outlined label="Term policy" class="col-3" name="term policy" id="term-policy"></q-select>
          <q-select rounded outlined label="is not" class="col-1" name="aplication" id="aplication"></q-select>
          <q-select rounded outlined label="" class="col-7" name="reason" id="reason"></q-select>
          <q-icon class="delete" name="close" />
        </div>
        <div class="row2 row justify-center space-between">
          <q-select rounded outlined label="Term policy" class="col-3" name="term policy" id="term-policy"></q-select>
          <q-select rounded outlined label="is not" class="col-1" name="aplication" id="aplication"></q-select>
          <q-select rounded outlined label="" class="col-7" name="reason" id="reason"></q-select>
          <q-icon class="delete" name="close" />
        </div>
        <div class="row3 row justify-center space-between">
          <q-select rounded outlined label="Term policy" class="col-3" name="term policy" id="term-policy"></q-select>
          <q-select rounded outlined label="is not" class="col-1" name="aplication" id="aplication"></q-select>
          <q-select rounded outlined label="" class="col-7" name="reason" id="reason"></q-select>
          <q-icon class="delete" name="close" />
        </div>
      </div>
        <div class="btn-group">
          <button class="and"> AND </button>
          <button class or> OR</button>
        </div>
    </section>
  </section>
</template>

<script>
export default {
  name: "PruebaTecnica",
  setup() {
    return {};
  },
};
</script>
