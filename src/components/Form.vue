<template>
  <div class="formCont">
    <form class="form" action="">
      <h1>Contact Us</h1>
      <div class="row">
        <div class="field">
          <label for="fN">First Name *</label>
          <input name="fN" type="text">
        </div>
        <div class="field">
          <label for="lN">Last Name *</label>
          <input name="lN" type="text">
        </div>
      </div>
      <div class="field">
          <label for="email">Email Address *</label>
          <input name="email" type="text">
      </div>
      <div class="field">
          <label for="">Query Type *</label>
          <div class="row">
            <button><img src="../assets/images/icon-radio-selected.svg" alt=""> General Enquiry</button>
            <button><img src="../assets/images/icon-radio-selected.svg" alt=""> Support Request</button>
          </div>
      </div>
      <div class="field">
          <label for="lN">Message *</label>
          <textarea cols="30" rows="10"></textarea>
      </div>
    </form>
  </div>
</template>

<style scoped>
  input{
    border-color: hsl(169, 82%, 27%);
    border-radius: 5px;
    min-width: none;
    width: 100%;
    height: 2rem;
  }

  button{
    border-color: hsl(169, 82%, 27%);
    border-radius: 5px;
    min-width: none;
    width: 100%;
    height: 2rem;
  }

  .formCont{
    display: flex;
    width: 55vw;
    height: 75vh;
    border-radius: 15px;
    flex-direction: column;
    background-color: hsl(0, 0%, 100%);
  }

  .form{
    max-width: 100%;
    margin: 5%;
  }

  .row{
    max-width: 100%;
    display: flex;
    flex-direction: row;
    gap: 24px;
    width: 100%;
  }
  .field{
    display: flex;
    width: 100%;
    flex-direction: column;
  }
</style>