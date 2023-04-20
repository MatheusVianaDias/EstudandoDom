// getElementById

const element = document.getElementById('blog-title')
console.log(element)


// getElementById

const element = document.getElementById('blog-title')
console.log(element)


// getElementByTagName

const element = document.getElementsByTagName('meta');
console.log(element)


// querySelector

const element = document.querySelector('')
console.log(element)


// querySelectorAll

const elements = document.querySelectorAll('.one')



elements.forEach(el => console.log(el))


MANIPULANDO CONTEUDO

// Manipulando conteúdo
// TextContent

const element = document.querySelector('h1')

element.textContent = "Olá Devs!"

// Manipulando conteúdo
// innerText 

const element = document.querySelector('h1')

element.innerText = "Olá devs!"



// Manipulando conteúdo
// innerHTML

const element = document.querySelector('h1')

element.innerHTML = "Olá Devs! <small> !!! </small>"


// Manipulando conteúdo
// value

const element = document.querySelector('input')

console.log(element.value)
element.value = "outro valor"