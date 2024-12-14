function openModal(type) {
    const modal = document.getElementById('modal');
    const modalText = document.getElementById('modal-text');
    modal.style.display = 'block';

    if (type === 'consulta') {
        modalText.textContent = 'Agende sua consulta preenchendo o formulário de contato!';
    } else if (type === 'planos') {
        modalText.textContent = 'Conheça nossos planos entrando em contato com nossa equipe.';
    }
}

function closeModal() {
    const modal = document.getElementById('modal');
    modal.style.display = 'none';
}
