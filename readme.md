# Proyecto de Programacion 4

_Este serie de archivos estan los trabajos propuestos y debidamente desarrollados_

## Participantes 🚀

Juan Salvador Mejia Diaz
Jorge Armando Gonzalez

## Ejercicio1

```JS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <div id="root"></div>
    
    <script type="text/babel">
        console.log("hola")
    
    const data={
    title_1:'Plato de la semana',
    title_2:'Berenjenas fritas',
    p_1:'Comensales: 4 personas',
    p_2:'Tiempo de preparacion: 10 minutos',
    p_3:'Tiempo de coccion: 12 minutos',
    p_4:'Ingredientes:',
    p_5:'4 berenjenas',
    p_6:'sal',
    p_7:'Pimienta',
    p_8:'4 cucharadas de harina y aceite',
    p_9:'Preparacion:',
    p_10:'Lavar las berenjenas',
    p_11:'Cortarlas en rodajas',
    p_12:'Espolvorearla con sal',
    p_13:'Dejar que suelten el agua durante 30 minutos',
    p_14:'Enharizarlas, ponerlas a freir durante 5 minutos en aceite bien caliente.',
    }
    
    const title_1x =<h1>{data.title_1}</h1> ;
    const title_2x= <h2>{data.title_2}</h2>;
    const p_1x=<p>{data.p_1}</p> ; 
    const p_2x=<p>{data.p_2}</p> ;
    const p_3x=<p>{data.p_3}</p> ;
    const p_4x=<p>{data.p_4}</p> ;
    const p_5x=<p>{data.p_5}<br/>{data.p_6}<br/>{data.p_7}<br/>{data.p_8}<br/>{data.p_9}</p> ;
    const p_10x=<p>{data.p_10}<br/>{data.p_11}<br/>{data.p_12}<br/>{data.p_13}<br/>{data.p_14}</p> ;

    
    const element=
    (
    <div>
    {title_1x}
    {title_2x}
    {p_1x}
    {p_2x}
    {p_3x}
    {p_4x}
    {p_5x}
    
    {p_10x}
  
    
    </div>
    
    
    )
    ReactDOM.render(element,document.getElementById('root'))
    
        </script>
    


    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    
</body>

</html>

## Ejercicio2

```JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    
    <div id="root"></div>

    <script type="text/babel">

const data={
  titulo:'Pagina Principal de Juan Jose Ospina',
  parrafo:'Bienvenido a mi pagina personal. Soy un alumno de la Universidad de Manizales y esta es mi pagina inicial, con la lista de mis enlaces favoritos y otros intereses',
  titulo2:'Enlaces Favoritos: ',
  listaOrdenada1:'Internet',
  listaOrdenada2:'Google',
  listaOrdenada3:'Aldea Global',
  listaOrdenada4:'Manual de HTML',
  encabezado:'Juan Jose, Universidad de Manizales, Octubre 2021',
}
  
const xtitulo=<h1>{data.titulo}</h1>;
const xtitulo2=<h2>{data.titulo2}</h2>;
const xparrafo=<p>{data.parrafo}</p>;
const xlistaOrdenada=<ol> <li>{data.listaOrdenada1}</li>  <li>{data.listaOrdenada2}</li> <li>{data.listaOrdenada3}</li> <li>{data.listaOrdenada4}</li> </ol>;
const xencabezado=<p><i>{data.encabezado}</i></p>;


    const element=(
<div>
    {xtitulo}
    {xparrafo}
    {xtitulo2}
    {xlistaOrdenada}
    {xencabezado}
    </div>

    )

 ReactDOM.render(element,document.getElementById("root"))
    </script>


<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>
</html>

## Ejercicio3

```JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    
    <div id="root"></div>

    <script type="text/babel">

const data={
  titulo:'Pagina Principal de Juan Jose Ospina',
  parrafo:'Bienvenido a mi pagina personal. Soy un alumno de la Universidad de Manizales y esta es mi pagina inicial, con la lista de mis enlaces favoritos y otros intereses',
  titulo2:'Enlaces Favoritos: ',
  listaOrdenada1:'Internet',
  listaOrdenada2:'Google',
  listaOrdenada3:'Aldea Global',
  listaOrdenada4:'Manual de HTML',
  encabezado:'Juan Jose, Universidad de Manizales, Octubre 2021',
}
  
const xtitulo=<h1>{data.titulo}</h1>;
const xtitulo2=<h2>{data.titulo2}</h2>;
const xparrafo=<p>{data.parrafo}</p>;
const xlistaOrdenada=<ol> <li>{data.listaOrdenada1}</li>  <li><a target='_blank' href="https://www.google.com/">{data.listaOrdenada2}</a></li> <li>{data.listaOrdenada3}</li> <li><a target='_blank' href="https://desarrolloweb.com/">{data.listaOrdenada4}</a></li> </ol>;
const xencabezado=<p><i>{data.encabezado}</i></p>;


    const element=(
<div>
    {xtitulo}
    {xparrafo}
    {xtitulo2}
    {xlistaOrdenada}
    {xencabezado}
    </div>

    )

 ReactDOM.render(element,document.getElementById("root"))
    </script>


<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>
</html>

## Ejercicio4

```JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    
    <div id="root"></div>

    <script type="text/babel">

const data={
  titulo:'Pagina Principal de Juan Jose Ospina',
  parrafo:'Bienvenido a mi pagina personal. Soy un alumno de la Universidad de Manizales y esta es mi pagina inicial, con la lista de mis enlaces favoritos y otros intereses',
  titulo2:'Enlaces Favoritos: ',
  listaOrdenada1:'Paginas Personales',
  listaOrdenada1_1:'Charkes F. Golfarb',
  listaOrdenada1_2:'Lou Burnard',
  listaOrdenada1_3:'Tim Berners-Lee',
  listaOrdenada2:'Paginas de referencia',
  listaOrdenada3:'Portales',
  listaOrdenada4:'Medios de comunicacion',
  encabezado:'Juan Jose, Universidad de Manizales, Octubre 2021',
}
  
const xtitulo=<h1>{data.titulo}</h1>;
const xtitulo2=<h2>{data.titulo2}</h2>;
const xparrafo=<p>{data.parrafo}</p>;
const xlistaOrdenada=<ol> <li>{data.listaOrdenada1} <ul> <li>{data.listaOrdenada1_1} </li> <li>{data.listaOrdenada1_2} </li> <li>{data.listaOrdenada1_3} </li>  </ul> </li>  <li>{data.listaOrdenada2}</li> <li>{data.listaOrdenada3}</li> <li>{data.listaOrdenada4}</li> </ol>;
const xencabezado=<p><i>{data.encabezado}</i></p>;


    const element=(
<div>
    {xtitulo}
    {xparrafo}
    {xtitulo2}
    {xlistaOrdenada}
    {xencabezado}
    </div>

    )

 ReactDOM.render(element,document.getElementById("root"))
    </script>


<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>
</html>

## Ejercicio5

```JS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

    <div id="root"></div>

    <script type="text/babel">


        const ptitulo = <h1>Pagina Principal de Juan Jose Ospina</h1>;
        const pparrafo = <p>Bienvenido a mi pagina personal. Soy un alumno de la Universidad de Manizales y esta es mi pagina inicial, con la lista de mis enlaces favoritos y otra informacion de interes</p>;

        const stitulo = <h2>Enlaces Favoritos</h2>;
        const slistaOrdenada = <ol> <li><a href="">Paginas personales </a></li>   <li>Paginas de referencia</li>   <li>Portales</li>   <li>Publicacion</li>  </ol>;

        const ttitulo = <h2>Paginas personales</h2>;
        const tlistaOrdenada = <ol> <li>Documentalistas  <ul> <li>Charkes F. Golfarb</li> <li>Lou Burnard</li> <li>Tim Berners-Lee</li> </ul>  </li>   <li>Historiadores</li>   <li>lingüstica</li>   <li>Traductores</li>  </ol>;

        const ctitulo=<h2>Paginas de referencia </h2> ;
       const clistaOrdenada=<ol> <li>Bibliotecas universitarias</li>  <li>Centros de documentacion </li>  <li>Museos de arte contemporaneo</li>  <li>Medios de comunicacion</li> </ol> ;

        const qtitulo =<h2>Portales</h2> ;
        const qlistaOrdenada = <ol> <li>Inicia</li> <li>Telepolis</li> <li>Ciudades</li> <li>Terra</li> </ol>;

        const utitulo =<h2>Publicaciones</h2> ;
        const ulistaOrdenada= <ol> <li>Ciberp@ís</li> <li>Diario Tecnologias de la Informacion</li> <li>The Standard</li> <li>Infoworld</li> <li>Wired</li> </ol>;
const fin=<p><i>Juan Jose Ospina, Universidad de Manizales, Octubre 2021. </i></p>;

        const element = (
            <div>
                {ptitulo}
                {pparrafo}
                {stitulo}
                {slistaOrdenada}
                <hr/>
                {ttitulo}
                {tlistaOrdenada}
                <hr/>
                {ctitulo}
                {clistaOrdenada}
                <hr/>
                {qtitulo}
                {qlistaOrdenada}
                <hr/>
                {utitulo}
                {ulistaOrdenada}
                <hr/>
                {fin}
            </div>

        )

        ReactDOM.render(element, document.getElementById("root"))
    </script>


    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>

</html>
## Ejercicio6

```JS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <div id="root"></div>
    <script type="text/babel">

        const titulo1 = <h1>El Noticiero Next University</h1>;
        const titulo1_1 = <h2>Programas de Tecnologia</h2>;
        const titulo1_2 = <h3>Desarrollador Web</h3>;
        const parrafo1 = <p><strong>Neut University</strong> lanza su programa de formación <strong>"Desarrollador Web"</strong> con la finalidad de capacitar a personas en
            las tendencias actuales sobre tecnologias, en el caso de desarrollo web, se basa temas relacionados a la
            implementación de Front-End con tecnologias y Frameworks, tales como: HTML5, CSS, JavaScript, Boostrap, entre
             <i> Otros.</i></p>
        const titulo1_3 = <h3>Android</h3>;
        const parrafo2=<p>En Nevt University te ofrecemos el programa Android que te da las herramientas necesarias para diseñar e
implementar aplicaciones Android para dispositivos móviles, partiendo de un conocimiento básico de Java, utilizando
el entorno de desarrollo Android Studio. Aprenderás los aspectos fundamentales para crear aplicaciones Android
interactivas, dinámicas y exitosas utilizando técnicas para el manejo de los recursos, datos, segundos planos,
localización, sensores, animaciones, gráficos, multimedia y monetizacion.</p>
const titulo1_4 = <h2>Programa de Negocio</h2>;

const titulo1_5 = <h3>Mercadeo Digital</h3>;

const parrafo3=<p>New University coloca a tu disposición de programa de <strong>"Mercadeo Digital".</strong> Sabias que...
Mercadeo Digital o
Digital Marketing es mucho más que hacer y publicar anuncios. Se trata del consumidor y la estrategia de negocio.
Estos son los puntos de partida para que cualquier acción de mercadeo digital sea exitoscy oprimice la inversión.
Este certificado. es un programa completo y práctico. que permite entender al consumidor la industria. la
competencia y los retos del negocio propio: para crear e implementar estrategias a la medida, en diferentes
plataformas y medios digitales. Por supuesto. monitoreando los resultados para tomar decisiones en tiempo real. </p>

        const element = (
            <div>
                {titulo1}
                {titulo1_1}
                {titulo1_2}
                {parrafo1}
                {titulo1_3}
                {parrafo2}
                {titulo1_4}
                {titulo1_5}
                {parrafo3}
            </div>

        )



        ReactDOM.render(element, document.getElementById("root"))
    </script>

    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>

</html>

## Ejercicio7

```JS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <div id="root"></div>
    <script type="text/babel">

        const titulos1 = <h1>Destinos Turisticos</h1>;
        const titulos2 = <h2>America</h2>;
        const lista =
            <ol>
                <li>Argentina
                    <ol>
                        <li>Buenos Aires</li>
                        <li>Bariloche</li>
                    </ol>
                </li>
                <li>Brasil <ol>
                    <li>Rio de Janeiro</li>
                    <li>Brasilia</li>
                </ol></li>
                <li>Chile<ol>
                    <li>Santiago</li>
                    <li>Valparaiso</li>
                </ol></li>
                <li>Colombia<ol>
                    <li>Bogota</li>
                    <li>Cartagena de Indias</li>
                </ol></li>
                <li>Estados Unidos<ol>
                    <li>New York</li>
                    <li>San Francisco</li>
                </ol></li>
                <li>Mexico<ol>
                    <li>Cancun</li>
                    <li>Acapulco</li>
                </ol></li>
                <li>Peru<ol>
                    <li>Lima</li>
                    <li>Cusco</li>
                </ol></li>
                <li>Venezuela<ol>
                    <li>Margarita</li>
                    <li>Mérida</li>
                </ol></li>
            </ol>;
        const element = (
            <div>
                {titulos1}
                {titulos2}
                {lista}
            </div>
        )
        ReactDOM.render(element, document.getElementById("root"))
    </script>

    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>

</html>

## Ejercicio8

```JS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>

<body>
    <div id="root"></div>
    <script type="text/babel">



        const titulo =
            <div className="container ">
                <div className="row">
                    <div class="col">
                        <img src="https://media.istockphoto.com/photos/group-of-people-raising-their-hands-against-a-sunset-picture-id1160644769" width="5%"></img>
                    </div>
                    <div class="col">
                        <p><strong>Tu Concierto</strong></p>
                    </div>
                </div>
            </div>

        const parrafo = <p>Bienvenido a este blog de conciertos...</p>;

        const img = <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJxora8wr4a1eUxGTMNga-GLjzseUIFy-kWg&usqp=CAU" width="50%"></img>
        const element = (
            <div>
                {titulo}
                {parrafo}
{img}
            </div>
        )

        ReactDOM.render(element, document.getElementById("root"))
    </script>

    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>
</body>

</html>

## Ejercicio9

```JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

</head>
<body>
    <div id="root"></div>
    <script type="text/babel">
    const titulo1=<h1><strong> Cartelera de vuelos - Aeropuerto el mirador</strong></h1>
    const titulo2=<h2><strong>Llegadas</strong></h2>
   
    const tabla=<table className="table">
  <thead>
    <tr>
      <th scope="col">Aerolinea</th>
      <th scope="col">Nro. vuelo</th>
      <th scope="col">Estatus</th>
      <th scope="col">Hora Estipulada</th>
      <th scope="col">Puerta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Airlan</td>
      <td>355</td>
      <td>Aterrizo</td>
      <td>2:45 PM</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Viajar</td>
      <td>556</td>
      <td>Retardado</td>
      <td>2:35pm</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Aerovuelo</td>
      <td>1234</td>
      <td>En vuelo</td>
      <td>3:45 PM</td>
      <td>8</td>
    </tr>
  </tbody>
</table>
const titulo3=<h2><strong>Salidas</strong></h2>
    const tabla2=<table className="table">
  <thead>
    <tr>
      <th scope="col">Aerolinea</th>
      <th scope="col">Nro. vuelo</th>
      <th scope="col">Estatus</th>
      <th scope="col">Hora Estipulada</th>
      <th scope="col">Puerta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Airlan</td>
      <td>355</td>
      <td>Embarcado</td>
      <td>2:15 PM</td>
      <td>1</td>
    </tr>
    
  </tbody>
</table>


const element=(
    <div>
        {titulo1}
        {titulo2}
        {tabla}
        {titulo3}
        {tabla2}
        </div>
)

    ReactDOM.render(element,document.getElementById("root"))
    </script>
    
    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>
</body>
</html>

## Ejercicio10

```JS
<!DOCTYPE html>
<html lang="en">

<head>
    <style>
        body {
            padding: 10px;
        }

        #listaol li {
            display: inline;
            padding-left: 3px;
            padding-right: 3px;
        }
    </style>

    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>

<body>
    <div id="root"></div>
    <script type="text/babel">



        const titulo =
            <div className="container ">
                <div className="row">
                    <div class="col">
                        <img src="https://static9.depositphotos.com/1621958/1180/i/950/depositphotos_11803523-stock-photo-chef-hat-icon-isolated.jpg" width="10%"></img>
                    </div>
                    <div class="col">
                        <p><strong>Recetas.com</strong></p>
                    </div>
                </div>
            </div>
        const lista = <ol id="listaol"> <a href=""><li>Recetas Principales</li></a> | <a href=""><li>Postres Latinos</li></a> </ol>;
        const parrafo1 = <p>Bienvenido a nuestro sitio web de gastronomia latina, te invitamos a preparar nuestras recetas</p>
        const t1=<h2>Nuevas Recetas</h2>
        const t2=<h3>**Arroz Criollo**</h3>
        const p1=<p>Tiempo de preparacion: <strong>45 minutos</strong> Numero de porciones <strong>4</strong> </p>
        const p2=<p><strong>Ingredientes</strong> </p>
        const lista1= <ul> 
            <li>Salsa de tomate</li>  
            <li>2 cucharadas de aceite 14gr</li>
            <li>1 cebolla larga 45gr</li>
            <li>2 dientes de ajo finamente picado 3gr</li>
            <li>1 pimenton rojo picado en cuadritos 60gr</li>
            <li>1 taza arroz blanco 225gr</li>
            <li>1 taza de maiz desgranado 79gr</li>
            <li>150gr de pechuga de pollo cocinado y desmechado</li>
            <li>sal al gusto</li>
            </ul>
            const p3=<p><strong>Preparacion</strong> </p>
            const lista2=<ol> 
            <li>Calentar en una olla el aceite, sofreir la cebolla junto con el ajo, el pimenton por 3 mintuos</li>  
            <li>Adicionar  el arroz y continua sofriendo para que se dore</li>
            <li>Agregar el pollo, el maiz desgranado y las verduras</li>
            <li>Mezclar todo, rectificar sal y dejar cocinar hasta que se seque</li>
            <li>Bajar el fuego, tapar la olla y continuar la coccion por 25 minutos mas</li>
            
            
            </ol>
        
        const p4=<p>Esta rica receta fue proporcionada por Maria Paula</p>
        
        const element = (
            <div>
                {titulo}
                {lista}
                {parrafo1}
                {t1}
                {t2}
                {p1}
                {p2}
                {lista1}
                {p3}
                {lista2}
                {p4}
            </div>
        )

        ReactDOM.render(element, document.getElementById("root"))
    </script>

    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>
</body>

</html>

## Ejercicio11

```JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div id="root"></div>
    <script type="text/babel">
    const t1=<h1>Registro en nuestra tienda</h1>
const formulario=<form>
    <label>Nombre usuario</label>
    <input placeholder="Ej: Name."></input>
<br/><br/>
    <label>Email</label>
    <input placeholder="Ej: example@gmail.com"></input>
    <br/>
    <br/>
    <label>Edad</label>
    <input placeholder="Ej: 10"></input>
    <br/>
    <br/>
    <label>Genero</label>
    <select name="select" >
        <option>Masculino</option>
        <option>Femenino</option>
        </select>
        <br/>
        <br/>
    <label>Recomendado por:</label>
    <select name="select" >
        <option>Google</option>
        <option>Otro</option>
        </select>
    <br/><br/>
    <label>Comentarios</label>
    <textarea  rows="10" cols="40"></textarea>
    <br/>
    <br/>
    <label>Acepto terminos y condiciones</label>
    <input type="checkbox"></input>
    <br/>
    <br/>
    <button type="submint">Registrar</button>

    </form>
const element=(
    <div>
        {t1}
        {formulario}
        </div>
)
    
    ReactDOM.render(element,document.getElementById("root"))
    </script>
    
    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>
</html>

## Ejercicio12

```JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div id="root"></div>
    <script type="text/babel">
    const t1=<h1>Titulo de encabezado</h1>
    const p1=<p>Descripcion del audio</p>
const video=<video type="video.mp4" width="640" height="480" controls></video>
    const p2=<p>Derechos Reservados(pie)</p>

const element=(
    <div>
        {t1}
        {p1}
        {video}
        {p2}
        </div>
)

    ReactDOM.render(element,document.getElementById("root"))
    </script>
    
    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>
</html>

## Ejercicio13

```JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div id="root"></div>
    <script type="text/babel">
    const t1=<h1>Titulo de encabezado</h1>
    const p1=<p>Este es un parrafo</p>
    const video=<iframe width="560" height="315" src="https://www.youtube.com/embed/z95mZVUcJ-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    const p2=<p>Derechos Reservados(pie)</p>

const element=(
    <div>
        {t1}
        {p1}
        {video}
        {p2}
        </div>
)

    ReactDOM.render(element,document.getElementById("root"))
    </script>
    
    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
</body>
</html>