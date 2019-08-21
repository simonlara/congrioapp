<template>
 <f7-page>
     <f7-navbar>
</f7-navbar>

<f7-list>
    <f7-list-input
    label="Raiz:"
    > </f7-list-input>
     <f7-list-input
    label="Nombre:"
    > </f7-list-input>
     <f7-list-item
    label="Logo:"
    
    >
     <font-awesome-icon slot="media" icon="user-secret" />
    </f7-list-item>
     <f7-list-input
    label="Foto Portada:"
    > </f7-list-input>
     <f7-list-input
    label="Descripción:"
    > </f7-list-input>
    <f7-list-input
    label="Twitter:"
    > </f7-list-input>
    <f7-list-input
    label="Topics:"
    > </f7-list-input>
     <f7-list-item
    header="Auspiciadores:"
    link="EditarAuspiciadores"
    after="Editar"
    > </f7-list-item>
     <f7-list-item
    header="Auspiciadores:"
    link="EditarAuspiciadores"
    after="Editar"
    > </f7-list-item>
     
       <f7-list-item 
    header="Modulos:"
    link="EditarModulos"
    after="Editar"
    > </f7-list-item>
    <f7-list-item
    header="Speakers:"
    link="EditarSpeakers"
    after="Editar"
    > </f7-list-item>
    <f7-list-item
    header="Venues:"
    link="EditarVenues"
    after="Editar"
    > </f7-list-item>
</f7-list>



 </f7-page>
</template>