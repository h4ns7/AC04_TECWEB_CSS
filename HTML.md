<!-- 
                                                            AC04 HTML STILO EM CSS
  DIEGO HANS MULLER, RA 1800306
  MATHEUS PIMENTEL TAVARES, RA 1800305
  MATHEUS MENDES, 18000330
  MATHEUS LACERDA, RA 18001135
  RAFAEL CAVALCANTI, RA 1800387 

-->

<DOCTYPE.html>

<html>


<head>
    <title>CSSFORM</title>
    <link rel="stylesheet" href="form.css">
</head>


<body>
    <header>

    <article>
        <section>
        <fieldset>
		
            <legend class="legend">Formulário</legend>
<center class="centerr">
            <form>
                
                <label for="nome">Nome Completo</label> <br/>
                <input type="text" name="nome"placeholder="Digite seu nome completo" 
	size="30"
	maxlength="20 " id="nome" >
<br/>
<br/>   
             
                <label for="endereço">Endereço</label><br/>
                <input type="text" name="endereço" placeholder="Preencha seu endereço" height"100px" id="endereço" maxlength="30">
<br/>
<br/>   
 
                <label for="cidade"><i>Cidade</i></label></br>
                <input type="text" name="cidade" placeholder="Digite sua cidade" height"100px" id="cidade" maxlength="20">
<br/>
<br/>   

		<label for="uf"><i>UF</i></label><br/>
		<input type="text" name="uf" placeholder="Preencha seu UF" height "100px" 	
id="uf" maxlength="2">
<br/>
<br/>   

		<label for="rg"><i>RG</i></label><br/>
		<input type="text" name="rg" placeholder="Preencha seu RG" height "100px" 	
id="uf" maxlength="9">
<br/>
<br/>   
 	<label for="cpf"><i>CPF</i></label><br/>
		<input type="text" name="cpf" placeholder="___.___.___-__ "size="15" 	
id="uf" maxlength="14">
<br/>
<br/>   
 	<label for="email">E-mail</label> <br/>
                <input type="text" name="e-mail" placeholder="Prencha seu e-mail"  size="29" id="email" maxlength="50">
<br/>
<br/>   


		<label for="text">Possui alguma rede social ?</label>		
		<input type="checkbox" id="check01" name="check01"/>
    		<label for="check01"><span></span>Facebook</label>
		<input type="checkbox" id="check02" name="check02"/>
    		<label for="check02"><span></span>Whatssap</label>
		<input type="checkbox" id="check03" name="check03"/>
    		<label for="check03"><span></span>Twitter</label>

<br/>
<br/>    

</centerr>
<label for="text">Cursos</label>
<select>

<option>Redes de computadores</option>
<option>Sistema da informação</option>
<option>Analise e desenvolvimento de sistemas</option>

</select>
<br/>
<br/>   

		<textarea id ="dados"  rows="4" cols="50" placeholder="Qual motivo da sua matricula na faculdade ?" maxlength="100"></textarea><br/><br/>
  	
               	<input type="submit" value= "Cadastrar">
		                
            </form>
        </fieldset>
        </section>
    </article>

    <footer>



    </footer>
    </header>

</body>

</html>
</DOCTYPE.html>
