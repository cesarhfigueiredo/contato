<!DOCTYPE html>
<html>
<head>
	<title>Formulario de Contato</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<form name="formteste" action="" method="post">
		<h1>Contato</h1>
	<p class="name">
			<label for="name">Nome:    </label><br>
			<input type="text" name="nome" placeholder="Informe seu nome" required="required"/>
		</p>
		<p class="birth">
			<label for="birth">Data de Nascimento:  </label><br>
			<input type="date" name="birth"  required="required"/>
		</p>
		<p class="telephone">
			<label for="telephone">Telefone:</label><br>
			<input type="tel" name="telephone" placeholder="Informe seu telefone" required="required"/><br>
			<label for="telephone">Telefone:</label><br>
			<input type="tel" name="telephone" placeholder="Informe seu telefone" />
		</p>
		<p>
			<label for="email">E-mail:</label><br>
			<input name="email" id="email" type="email" placeholder ="Informe o E-mail"/ required="required">
		</p>
		<p class="">
			<label for="endereco">Endereço:</label><br>
			<input type="text" name="endereço" placeholder="" required="required"/><br>
			<label for="number">Numero:</label><br>
			<input type="number" name="numero" placeholder="" required="required"/><br>
			<label for="texto">Complemento:</label><br>
			<input type="text" name="texto" placeholder="" /><br>
			<label for="bairro">Bairro:</label><br>
			<input type="text" name="bairro" placeholder="" required="required"/><br>
			<label for="city">Cidade:</label><br>
			<input name="city" type="text" placeholder ="" required="required"/><br>
			<label for="uf">Estado:</label><br>
			<select name="uf" type="text" placeholder ="" required="">
				<option value="" ></option>
				<option value="AC">Acre</option>
				<option value="AL">Alagoas</option>
				<option value="AP">Amapá</option>
				<option value="AM">Amazonas</option>
				<option value="BA">Bahia</option>
				<option value="CE">Ceará</option>
				<option value="DF">Distrito Federal</option>
				<option value="ES">Espírito Santo</option>
				<option value="GO">Goiás</option>
				<option value="MA">Maranhão</option>
				<option value="MT">Mato Grosso</option>
				<option value="MS">Mato Grosso do Sul</option>
				<option value="MG">Minas Gerais</option>
				<option value="PA">Pará</option>
				<option value="PB">Paraíba</option>
				<option value="PR">Paraná</option>
				<option value="PE">Pernambuco</option>
				<option value="PI">Piauí</option>
				<option value="RJ">Rio de Janeiro</option>
				<option value="RN">Rio Grande do Norte</option>
				<option value="RS">Rio Grande do Sul</option>
				<option value="RO">Rondônia</option>
				<option value="RR">Roraima</option>
				<option value="SC">Santa Catarina</option>
				<option value="SP">São Paulo</option>
				<option value="SE">Sergipe</option>
				<option value="TO">Tocantins</option>
			</select>
			<br>
		</p>
		<p class="enviar">
			<input type="submit" name="enviar" value="Enviar">
		</p>
		<p class="resetar">
			<input type="reset" name="resetar" value="Resetar"> 
		</p>
</form>
</body>
</html>
