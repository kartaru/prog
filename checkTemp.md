function checkTemp(c) {
    if (c <= 20) {
        return (-1)
    }
    else if (c > 40) {
        return (1)
    }
    else {
        return (0)
    }
}
console.log(checkTemp (21));
