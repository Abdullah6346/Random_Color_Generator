# Random_Color_Generator
function getrandomcolor() {
    var hash = '#';
    var hexcode = '0123456789ABCDEF'
    for (let i = 0; i < 6; i++) {
        hash += hexcode[Math.floor(Math.random() * 16)];
    }
    return hash
}

I have written this function to create random colours . 
I have used hex colour codes but other colour schemes such as Rgba and HSl can also be used
