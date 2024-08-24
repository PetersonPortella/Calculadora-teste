let contador = 0;
let input = document.getElementById('input-add');
let btn = document.getElementById('button-add');
let main = document.getElementById('lista');

function addTarefa(){
    //pegar o que esta digitado no input
    let valorInput = input.value;

    //se não for vazio,null ou indefinido  
    if ((valorInput !=="")  &&  (valorInput!==null) && (valorInput!==undefined)){

        ++contador;

        let novoItem = `<div id="${contador}" class="item">

            <div class="item-icone">
                <span  id="icone_${contador}" onclick="marcar(${contador})" class= "material-symbols-outlined"> circle </span>
            </div>

            <div onclick="marcar(${contador})" class="item-texto">
                ${valorInput}
            </div>

            <div class="item-botao">
                <button onclick="del(${contador})" class="deletar"><span class="material-symbols-outlined">
                     delete
                </span>Deletar</button>
            </div>

            </div>`;

            //adicionar o item no no main
            main.innerHTML += novoItem;

            //zerar o input
            input.value = "";
            input.focus();
        }
}  

function del(id){ //deletar as tarefas
    var tarefa = document.getElementById(id);
    tarefa.remove();

}

function marcar(id) { //funçaõ de criar a lista e modificar
    var item = document.getElementById(id);
    var icone = document.getElementById("icone_" + id);
    var classe = item.getAttribute('class');
    
    if (classe == 'item') {
        item.classList.add('item-clicado');  //Adiciona ou exlui uma ou mais classes ao elemento.
        icone.textContent = "check_circle";  // Alterar o ícone para "check_circle"
    } else {
        item.classList.remove('item-clicado');
        icone.textContent = "circle";  // Alterar o ícone de volta para "circle"
    }
}

input.addEventListener("keyup", function (event){ //add uma tarefa com o botão "enter"
    //se clicar enter(13 numero do botão enter)
    if(event.keyCode === 13){
        event.preventDefault();
        btn.click();
    }
})
