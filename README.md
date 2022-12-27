# modal-module
Simple modal module with 3 parameters:

1) triggerSelector - [data-modal] 
2) modalSelector - .modal class
3) modalTimerId - const modalTimerId = setTimeout(() => openModal('.modal', modalTimerId), 50000);

Example of modal call():
<br>
modal('[data-modal]', '.modal', modalTimerId);
