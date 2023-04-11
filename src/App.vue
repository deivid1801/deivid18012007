<script setup>
</script>

<template>
  <div class="app">
    <p>Nome:</p>
    <input v-model="nome" />
    <p>CPF:</p>
    <input type="text" class="form-control cpf-mask" placeholder="">
    <p>Email:</p>
    <input type="email" v-model="email" />
    <p>Telefone:</p>
    <input type="text" class="form-control phone-ddd-mask" placeholder="">
    <P>Data de nascimento:</P>
    <input type="text" class="form-control date-mask" id="example-input-1" placeholder="" maxlength="10"
      autocomplete="off">
    <p>Endereço:</p>
    <p><select >
        <option value="0" selected="selected">Cidade</option>
        <option value="10167">ÁGUAS FRIAS</option>
        <option value="10180">ANCHITA</option>
        <option value="6551">ARAQUARI</option>
        <option value="6550">ARARANGUA</option>
        <option value="6544">BALNEÁRIO CAMBURIU</option>
        <option value="6117">BALNEÁRIO PIÇARRAS</option>
        <option value="10182">BARRA BONITA</option>
        <option value="10183">BELMONTE</option>
        <option value="6541">BIGUAÇU</option>
        <option value="6540">BLUMENAL</option>
        <option value="10165">BOMBINHAS</option>
        <option value="6536">BRUSQUE</option>
        <option value="6535">CAÇADOR</option>
        <option value="6213">CAIBI</option>
        <option value="6212">CAMBURIÚ</option>
        <option value="6208">CAMPOS NOVOS</option>
        <option value="6206">CANOINHAS</option>
        <option value="7397">CAPIVARI DO BAIXO</option>
        <option value="10166">CAXAMBU DO SUL</option>
        <option value="6202">CHAPECÓ</option>
        <option value="7773">COCAL DO SUL</option>
        <option value="6201">CONCORDIA</option>
        <option value="6045">CORREIA PINTO</option>
        <option value="10162">CORUPÁ</option>
        <option value="6198">CRICIUMA</option>
        <option value="6197">CUNHA PORA</option>
        <option value="6196">CURITIBANOS</option>
        <option value="6195">DESCANSO</option>
        <option value="6194">DIONIO CERQUEIRA</option>
        <option value="10184">FLOR DO SERTÃO</option>
        <option value="6190">FLORIANOPOLIS</option>
        <option value="9999">FORQUILHA</option>
        <option value="6187">GORVERNADOR CELSO RAMOS</option>
        <option value="6181">GUABIRUBA</option>
        <option value="6180">GUARACIABA</option>
        <option value="6179">GUARAMIRIM</option>
        <option value="6178">GUARUJA DO SUL</option>
        <option value="6174">ICARA</option>
        <option value="6173">ILHOTA</option>
        <option value="5588">IPORA DO OESTE</option>
        <option value="5587">IRACEMINHA</option>
        <option value="6162">ITAJAÍ</option>
        <option value="10160">ITAPEMA</option>
        <option value="6155">JARAGUÁ DO SUL</option>
        <option value="6154">JOAÇABA</option>
        <option value="6153">JOINVILLE</option>
        <option value="6151">LAGES</option>
        <option value="6150">LAGUNA</option>
        <option value="6143">MAFRA</option>
        <option value="6999">MARACAJÁ</option>
        <option value="6140">MARAVILHA</option>
        <option value="6136">MODELO</option>
        <option value="6135">MONDAI</option>
        <option value="6132">NAVEGANTES</option>
        <option value="6131">NOVA ERECHIM</option>
        <option value="6130">NOVA TRENTO</option>
        <option value="6128">OORLEANS</option>
        <option value="6126">PALHOÇA</option>
        <option value="6125">PALMA SOLA</option>
        <option value="10175">PALMITOS</option>
        <option value="10185">PARAISO</option>
        <option value="6120">PENHA</option>
        <option value="6116">PINHALZINHO</option>
        <option value="6110">PORTO BELO</option>
        <option value="6109">PORTO UNIÃO</option>
        <option value="6097">RIO DO SUL</option>
        <option value="10163">RIO NEGRINHO</option>
        <option value="10187">RIQUEZA</option>
        <option value="6093">ROMELANDIA</option>
        <option value="10188">SANTA HELENA</option>
        <option value="10164">SANTA TEREZINHA DO PROGRESSO</option>
        <option value="6088">SANTO AMARO DA IMPERATRIZ</option>
        <option value="6087">SÃO BENTO DO SUL</option>
        <option value="7012">SAO CARLOS</option>
        <option value="6083">SAO FRANCISCO DO SUL</option>
        <option value="6082">SAO JOAO BATISTA</option>
        <option value="10189">SAO JOAO DO OESTE</option>
        <option value="6080">SAO JOAQUIM</option>
        <option value="6079">SAO JOSE</option>
        <option value="6078">SAO JOSE DO CEDRO</option>
        <option value="6076">SAO LOURENCO DO OESTE</option>
        <option value="6073">SAO MIGUEL DO OESTE</option>
        <option value="6072">SAUDADES</option>
        <option value="6071">SCHROEDER</option>
        <option value="10176">SERRA ALTA</option>
        <option value="6068">SOMBRIO</option>
        <option value="10177">SUL BRASIL</option>
        <option value="10191">TIGRINHOS</option>
        <option value="6065">TIJUCAS</option>
        <option value="6059">TUBARÃO</option>
        <option value="10192">TUNÁPOLIS</option>
        <option value="10178">UNIAO DO OESTE</option>
        <option value="6056">URUSSANGA</option>
        <option value="6053">VIDEIRA</option>
        <option value="6051">XANXERE</option>
        <option value="6050">XAVANTINA</option>
        <option value="6049">XAXIM</option>
      </select>
      <select class="form-control form-control-lg">
        <option value="0" selected="selected">Estado</option>
        <option>AC</option>
        <option>AL</option>
        <option>AP</option>
        <option>AM</option>
        <option>BA</option>
        <option>CE</option>
        <option>DF</option>
        <option>ES</option>
        <option>GO</option>
        <option>MA</option>
        <option>MT</option>
        <option>MS</option>
        <option>MG</option>
        <option>PA</option>
        <option>PB</option>
        <option>PR</option>
        <option>PE</option>
        <option>PI</option>
        <option>RJ</option>
        <option>RN</option>
        <option>RS</option>
        <option>RO</option>
        <option>RR</option>
        <option>SC</option>
        <option>SP</option>
        <option>SE</option>
        <option>TO</option>
      </select>
    </p>
    <p>Bairro:</p>
    <p><input type="text" class="form-control form-control-lg" placeholder=""></p>
    <p>Rua/Avenida/Br:</p>
    <p><input type="text" class="form-control form-control-lg" placeholder=""></p>
    <p>Número da casa/apartamento:</p>
    <p><input type="text" class="from-control" placeholder=""></p>

    <p>Senha:</p>
    <input type="password" v-model="senha" />
    <p>Confirma senha:</p>
    <input type="password" v-model="confirmaSenha" />
    <form>
      <div class="form-check mb-3">
        <label class="form-check-label">
          <p>
            <input class="form-check-input" type="checkbox" name="remember"> Lembrar dados
          </p>
        </label>
      </div>
      <div class="li">
        <td data-align="center"
          style="text-align:-khtml-center;text-align:-moz-center;text-align:-webkit-center;height:25px"
          class="gx-tab-padding-fix-1   ">&nbsp;<span class="CheckBox"
            style="font-family:'Microsoft Sans Serif'; font-size:12.0pt; font-weight:normal; font-style:normal;"><input
              type="checkbox" id="vISCONFIRMED" name="vISCONFIRMED" value=""
              onfocus="gx.evt.onfocus(this, 49,'',false,'0002',0)"
              onclick="gx.fn.checkboxClick(49, this, 'true', 'false','');gx.evt.onchange(this, event);"
              onblur=";gx.evt.onblur(this,49);" data-gx-context="[&quot;&quot;,false]"><label data-gx-checkbox-title=""
              for="vISCONFIRMED">Li e concordo com todos os termos e condições.</label>
          </span>
        </td>
      </div>
      <button type="submit" class="btn btn-primary">Confirma</button>
    </form>
  </div>
</template>

<style>
.app {
  margin-left: auto;
  margin-right: auto;
}

button {
  background-color: rgb(129, 255, 158);
  text-align: center;
  border-radius: 7.5px;
  box-shadow: 3px 3px 1px #41065c;
  transition: transform 1s;
}

button:hover,
button:focus {
  background: rgb(98, 255, 135);
  transform: translateX(12px) scale(1.2);
  box-shadow: 4px 4px 2.5px #41065c;
}


input {
  border-radius: 5px;
  margin-top: 5px;
  box-shadow: 4px 2px 1.5px #41065c;
}

p {
  font-style: italic;
  font-weight: bolder;
  color: rgb(255, 255, 255);
}

select {
  border-radius: 5px;
  margin-top: 5px;
  box-shadow: 4px 2px 1.5px #41065c;
}

.li {
  margin-left: auto;
  margin-right: auto;
  font-style: italic;
  font-weight: bolder;
  color: rgb(255, 255, 255);

}</style>
