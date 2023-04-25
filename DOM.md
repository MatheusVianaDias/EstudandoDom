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


// Manipulando conteúdo
// Atributos

const header = document.querySelector('header')
header.setAttribute('id', 'header')

const headerID = document.querySelector('#header')

console.log(headerID.getAttribute('class'))

header.removeAttribute('id')

header.setAttribute('class', 'bg header')


// Alterar estilos

const element = document.querySelector('body')

element.style.backgroundColor = "#f9f3d2"
console.log(element.style.backgroundColor)

// Alterar estilos
// classList

const element = document.querySelector('body')

element.classList.add('active', 'green')

console.log(element.classList)
element.classList.remove('active')
element.classList.toggle('active')

// Navegando pelos elementos
// parentNode parentElement
const element = document.querySelector('h1')

console.log(element.parentElement)


//Navegando pelos elementos
//childNodes children

const el = document.querySelector('body')

//firstChild firstElementchild



// lastchild lastElementChild
console.log(el.lastElementChild)


// Navegando pelos elementos

const el = document.querySelector('body script')

// nextSibling nextElementSibling



// previousSibling previousElementSibling
console.log(el.previousElementSibling)


//  Criando e adicionando elementos

//createElement
const div = document.createElement('div');
div.innerText = "Olá devs!"


// append prepend

const body = document.querySelector('body')

body.prepend(div)

// Adicionando elementos
const div = document.createElement('div')
div.innerText = "Olá divs!"

// insertBefore
const body = document.querySelector('body')
const script = body.querySelector('script')
body.insertBefore(div, script)


// Adicionando eventos 

const input = document.querySelector('input')

input.onkeypress = function(){
    console.log('rodei')
}