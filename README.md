// javascript-test-0001-final-19619-siddhant
//Final Project Assignment - This repository contains the complete final project code and documentation.
let n = 5;

for (let i = 1; i <= n; i++) {
    let row = "";

    // spaces
    for (let j = 1; j <= n - i; j++) {
        row += " ";
    }

    // stars
    for (let j = 1; j <= (2 * i - 1); j++) {
        if (j === 1 || j === (2 * i - 1)) {
            row += "*";
        } else {
            row += " ";
        }
    }

    console.log(row);
}

// lower part
for (let i = n - 1; i >= 1; i--) {
    let row = "";

    for (let j = 1; j <= n - i; j++) {
        row += " ";
    }

    for (let j = 1; j <= (2 * i - 1); j++) {
        if (j === 1 || j === (2 * i - 1)) {
            row += "*";
        } else {
            row += " ";
        }
    }

    console.log(row);
}
