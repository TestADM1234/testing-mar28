# testing-mar28

// before rename
const x = {
    y: 'value'
}
const { y } = x;
console.log(y);

// after rename
const x = {
    z: 'value'
}
const { z: y } = x;
console.log(y);

