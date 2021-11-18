# Alert-CreateParag

<button id='b1'>Cliquez moi</button>
        <button id='b2'>Ajouter un paragraphe</button>
        
 // creer un bouton qui fait une alert
 // crrer un bouton pour ajouter un paragraphe

let bonjour = document.getElementById('b1');
let ajouter = document.getElementById('b2');

bonjour.addEventListener('click', alerte);
ajouter.addEventListener('click', ajout);

function alerte(){
    alert('Bonjour');
}
function ajout(){
    let para = document.createElement('p');
    para.textContent = 'Paragraphe ajouté';
    document.body.appendChild(para);
}
