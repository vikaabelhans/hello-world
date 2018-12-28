# hello-world
just another repository
'use strict';
var name = '';
var alter = '';
const erwachsen = 18;

name = prompt('Bitte geben Sie Ihren Namen ein!', name);
alter = prompt('Bitte geben Sie Ihren Namen ein!', alter);

if (alter < erwachsen) {
    alter('Du kommst hier nicht rein!')
}
else {
      var ausgabe = 'Hallo, ' + name;
      alert(ausgabe);
} 
