var app = new Vue({
  el: "#app",
  methods:{
    sendMsg(){
      eval( 'var msg = ' +$('#message').val()+';');   
      liff.sendMessages(msg);

    }
  }
});