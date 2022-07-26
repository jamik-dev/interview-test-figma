<template>
    <v-container fluid>
        <div class="aligning">
            <div class="dark_color main-part">
                <p class="brand_logo" style="text-align: center; margin-top: 80px">Brand Logo</p>
                <div class="form-wrapper border-form" style="margin-top: 64px">
                    <p class="form_title" style="text-align: center">Добавить компанию</p>
                    <form style="margin-top: 32px;" action="">
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Name</span>
                                </label>
                            </v-col>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="tel" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Phone number</span>
                                </label>
                            </v-col>
                        </v-row>
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Location</span>
                                </label>
                            </v-col>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Address</span>
                                </label>
                            </v-col>
                        </v-row>
                        <div class="divider"></div>
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">ИНН</span>
                                </label>
                            </v-col>
                        </v-row>
                        <div class="divider"></div>
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Company Director</span>
                                </label>
                            </v-col>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Company name</span>
                                </label>
                            </v-col>
                        </v-row>
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Company Address</span>
                                </label>
                            </v-col>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Register date</span>
                                </label>
                            </v-col>
                        </v-row>
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Company phone</span>
                                </label>
                            </v-col>
                        </v-row>
                        <div class="divider"></div>
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">MFO</span>
                                </label>
                            </v-col>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Payment account</span>
                                </label>
                            </v-col>
                        </v-row>
                        <v-row>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">Reg. code vat</span>
                                </label>
                            </v-col>
                            <v-col cols="12" md="6" sm="12">
                                <label class="over_input">
                                    <input type="text" required placeholder=" " class="input_field">
                                    <span class="over_placeholder">OKED</span>
                                </label>
                            </v-col>
                        </v-row>
                        <div class="btn-wrapper">
                            <input type="submit" class="form-btn" value="Далее">    
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </v-container>
</template>

<script>
export default {
    name: 'Login-View',
    data: () => ({

    })
}
</script>

<style>
.v-application--wrap{
    background-color: #24282D;
    color: #fff;
}
.aligning{
    display: flex;
    align-items: center;
    justify-content: center;
}
.border-form{
    border: 1px solid #373D45;
    border-radius: 6px;

}
.brand_logo{
    font-family: Ubuntu;
    font-weight: 500;
    font-size: 32px;
    line-height: 120%;
}
.form-wrapper{
    height: auto;
    width: 840px;
    padding: 16px;
}
.form_title{
    font-family: 'Roboto';
    font-weight: 400;
    font-size: 20px;
    line-height: 150%;
}
.divider{
    height: 1px;
    width: 100%;
    margin: 20px 0;
    background-color: #434C57;
}
.input_field{
    height: 48px;
    background-color: #2F343B;
    border: 1px solid #373D45;
    border-radius: 6px;
    outline: none;
    padding: 12px 12px 12px 16px;
    color: #fff;
    width: 100%;
}
.col-md-6{
    padding: 8px; 
}
.btn-wrapper{
    margin-top: 20px;
    display: flex;
    justify-content: center;
}
.form-btn {
    padding: 10px 24px;
    background: #0496FF;
    border-radius: 8px;
    font-family: 'Roboto';
    font-weight: 400;
    font-size: 14px;
    line-height: 140%;
    
}


.over_input {
  position:relative;
  display:inline-block;
  width: 100%;
}
  
.over_placeholder {
  padding:0 4px;
  background: #2F343B;
  border-radius: 4px; 
  pointer-events: none;
  position:absolute;
  left:16px;
  top: 50%;
  transform: translate(0, -50%);
  color: #ADB5BD!important;
  font-family: 'Roboto';
  transition: 0.2s;
  transition-timing-function: ease;
  transition-timing-function: cubic-bezier(0.25, 0.1, 0.25, 1);
}
input:focus + span, input:not(:placeholder-shown) + span {
  color: #6C757D;
  letter-spacing: 0.05em;
  transform: scale(0.75) translateY(-200%) translateX(-15%);
}

input:focus + span, input:not(:-ms-input-placeholder) + span {
  color: #6C757D;
  letter-spacing: 0.05em;
  transform: scale(0.75) translateY(-100%) translateX(-30px);
}

/* responsivity */

@media (min-width: 601px) and (max-width: 959px) {
    .form-wrapper{
        width: 430px;
    }
}
@media (min-width: 0px) and (max-width: 600px) {
    .form-wrapper{
        width: 320px;
    }
}
</style>