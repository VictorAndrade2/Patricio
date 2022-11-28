body {
    background: rgb(169,169,169);
    color: #FFF;
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1rem;
}

.conteudo {
    margin: 0 auto;
    width: 100%;;
    max-width: 450px;
    margin-top: 50px;
    margin-bottom: 50px;
    background: #2b2a2a;
    padding: 55px;
    border-radius: 12px;
}

.topo {
   display: flex;
   justify-content: space-between;
   margin-bottom: 35px;     
}

.topo input {
    width: 350px;
    padding: 15px;
    border-radius: 12px;
    border: 1px solid #191819;
    outline: none;
    font-size: 1.2rem;
    background: #2F4F4F;
    color: #00FFFF;
}

.topo button {
    width: 45px;
    border-radius: 12px;
    border: 1px solid #191818;
    background: #2F4F4F;
    color: #00FFFF;
    outline: none;
}

.topo button:hover {
    background: #836FFF;
    cursor: pointer;
}

#listaTarefas {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

#listaTarefas li {
    padding: 20px;
    background: #008080;
    border-radius: 12px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 20px;
}

.btnAcao {
    border-radius: 20px;
    border: 1px solid #191818;
    width: 38px;
    height: 38px;
    margin-right: 8px;
    cursor: pointer;
    background: #2b2a2a;
    color: #DAA520;
    outline: none;
}

.btnAcao:hover {
    background: #3c3a3a;
}

.textoTarefa {
    overflow: hidden;
    text-overflow: ellipsis;
    width: 290px;
    white-space: nowrap;
}

#janelaEdicao {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 20px;
    background: #006400;
    border: 1px solid #2f2e2e;
    width: 415px;
    border-radius: 12px;
    z-index: 200;
    display: none;
}

#janelaEdicao.abrir {
    display: block !important;
}

#janelaEdicaoFundo {
    position: fixed;
    top: 0;
    background-color: #FFF;
    bottom: 0;
    left: 0;
    opacity: 0.9;
    z-index: 100;
    right: 0;
    display: none;
}

#janelaEdicaoFundo.abrir {
   display: block !important;    
}

#janelaEdicaoBtnFechar {
    position: absolute;
    top: -25px;
    right: -18px; 
    width: 50px;
    height: 50px;
    border-radius: 50%;
    border: 1px solid #2d2c2c;
    background: #2d2c2c;
    color: #DAA520;
    outline: none;
}

form {
    width: 100%;
    margin-top: 20px;
}

.frm-linha {
    display: flex;
    flex-direction: column;
    margin-bottom: 20px;
}

.frm-linha label {
    margin-bottom: 7px;
}

.frm-linha input {
    padding: 15px;
    border-radius: 12px;
    outline: none;
    border: 1px solid #191818;
    font-size: 1.2rem;
    background: #2d2c2c;
    color: #DAA520;
}

.frm-linha button {
    background: #2d2c2c;
    border: 1px solid #191818;
    padding: 7px;
    margin-bottom: 10px;
    border-radius: 12px;
    color: #DAA520;
    cursor: pointer;
    height: 50px;
    font-size: 1.3rem;
    outline: none;
}

.frm-linha button:hover {
    background: #3c3a3a;
} 

