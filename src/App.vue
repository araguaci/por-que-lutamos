 <template>
  <div>

     <p>Que as gotas de chuva molhem suavemente o seu rosto.</p>
     <p>Que o vento suave refresque seu espírito.</p>
     <p>Que o sol ilumine o seu coração.</p>
     <p>Que as tarefas do dia não sejam um peso nos seus ombros.</p>
     <p>Que Deus envolva você no manto de seu amor.</p>
     <p>Que a estrada se abra à sua frente.</p>
     <p>Que o vento sopre levemente em suas costas.</p>
     <p>Que o sol brilhe morno e suave em sua face.</p>
     <p>Que a chuva caia de mansinho em seus campos.</p>
     <p>Até que nos encontremos de novo...</p>
     <p>Que Deus guarde você na palma de sua mão.</p>
     
     <h3>SANTO, SANTO, SANTO, É O SENHOR DAS HOSTES DO UNIVERSO</h3>
     <h3>918197185    3396815  138 14111963    71042    419 814</h3>
  </div>  
</template>
<script>
export default {  
  mounted() {
    setTimeout(this.openPdf(), 3000);
  },
  methods: {
    openPdf() {
      setTimeout(function(){
        const file = 'manifesto-da-resistencia-europeia.pdf' // 将'your-file-name'替换为实际的文件名
        window.open(`/${file}`, '_self')
      }, 7000);      
    }
  }  
}
</script>
<style>
  html {
    background: hsla(143, 100%, 29%, 0.73);
    background: linear-gradient(0deg, hsla(52, 100%, 50%, 1) 0%,  hsla(143, 100%, 29%, 1) 50%, hsla(220, 100%, 23%, 1) 100%);
    background: -moz-linear-gradient(0deg, hsla(52, 100%, 50%, 1) 0%, hsla(143, 100%, 29%,  1) 50%,   hsla(220, 100%, 23%, 1) 100%);
    background: -webkit-linear-gradient(0deg, hsla(52, 100%, 50%, 1) 0%, hsla(143, 100%, 29%, 1) 50%,   hsla(220, 100%, 23%, 1) 100%);
    filter: progid: DXImageTransform.Microsoft.gradient( startColorstr="#FEDD00", endColorstr="#009639", GradientType=1 );
  }
  div {
    padding-top: 10px;
    margin: auto 10px;
    font-size:xx-large;
  }
  p {
    color: whitesmoke;
    text-align: center;
    margin: 5px;
    line-height: normal;
  }
  h3 {
    text-align: center;
    color: #FEDD00;
    font-size: medium;
  }
</style>
