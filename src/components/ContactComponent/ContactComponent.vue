<template src="./ContactComponent.html"/>

<script>
import emailjs from 'emailjs-com';

export default {
  name: "ContactComponent",

  data: function(){
    return({
      contact_name: "",
      contact_email: "",
      contact_msg: "",
    })
  },

  methods: {
    onSubmit: function(e){
      emailjs
        .sendForm("gmail", "template_FLa5PMsO", e.target, "user_gGrCPTun7gA5vwb9V8o4b")
        .then(() => {
          alert("Thank you for your interest. I will get back to you ASAP.");
          this.contact_name = "";
          this.contact_email = "";
          this.contact_msg = "";
        }, () => {
          alert("Something went wrong")
        })
    }
  }
}
</script>

<style lang="scss" scoped src="./ContactComponent.scss"/>