let numb = 10
for(; numb < 52; numb = numb+2) {
    console.log(numb);
}

const me = {
    name: 'Max',
    surname: 'Pachomkin',
    age: 19,
    animal: 'Nope'
};
console.log(me);

const array = [
    'я в Симбирск,',
    'в трактире.',
    'с утра',
    'В ту же ночь',
    'Я остановился',
    'для закупки', 
    'что и было поручено Савельичу.',
    'приехал,',
    'где должен был',
    'нужных вещей',
    'отправился по лавкам',
    'пробыть сутки',
    'Савельич'
];

let result = `${array[3]} ${array[7]} ${array[0]} ${array[8]} ${array[11]} ${array[5]} ${array[9]} ${array[6]} ${array[4]}  ${array[1]}  ${array[12]} ${array[2]} ${array[10]}`;
console.log(result);

homeWork('Max' , 'Pachomkin');

function homeWork (firstName, lastName) {
    const fullName = `${firstName} ${lastName}`;
    console.log(fullName);
}


let y = 19;
while (y < 67) {
    y = y + 2;
    console.log(y);
}
