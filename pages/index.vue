<template>
  <div class="template bg-white">
    <nav class="fixed w-full px-6 py-2 flex justify-between items-center bg-gray-800">
      <!--Logo-->
      <a class="text-3xl font-bold leading-none" href="#">
        <img class="h-12 px-4" src="https://lh3.googleusercontent.com/proxy/mvP2sHgAls-qoydUprfVCGGDkuQWcVC3uZareXjtShGK2hSAYl_ccecFYrgj8N3pisv2epB-tPSRDIl1KK0LoUY7ZGYVGk7ix57qoFRzg7b4Iru_Tbgf88Fnp5TaryS2eXPz" alt="" width="auto">
      </a>
      <!--Menu hamburguesa-->
      <div class="lg:hidden">
        <button class="navbar-burger flex items-center text-green-600 p-3">
          <svg class="block h-4 w-4 fill-current" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" >
            <title>
              Mobile menu
            </title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
        </button>
      </div>
      <!--Menu-->
      <ul class="hidden relative top-1/2  transform lg:flex lg:items-center lg:w-auto lg:space-x-6">
        <li><a class="text-sm text-white hover:text-green-600 font-bold" href="http://localhost:3000/">Inicio</a></li>
        <li class="text-gray-300">
          <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"></path>
          </svg>
        </li>
        <li><a class="text-sm text-white hover:text-green-600 font-bold" href="http://localhost:3000/desarrollos">Desarrollos Playa del Carmen</a></li>
        <li class="text-gray-300">
          <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"></path>
          </svg>
        </li>
        <li><a class="text-sm text-white hover:text-green-600 font-bold" href="http://localhost:3000/blog">Desarrollos Tulum</a></li>
      </ul>

      <!--Botones-->
      <a class="hidden lg:inline-block lg:ml-auto lg:mr-3 py-2 px-6 bg-gray-50 hover:bg-gray-100 text-sm text-gray-900 font-bold rounded-l-xl rounded-t-xl transition duration-200" href="#">
        Iniciar sesion
      </a>
      <a class="hidden lg:inline-block py-2 px-6 bg-green-500 hover:bg-green-600 text-sm text-white font-bold rounded-l-xl rounded-t-xl transition duration-200" href="https://web.whatsapp.com/send?phone=+529841642844&text=Estoy%20interesado%20en%20recibir%20m%C3%A1s%20informaci%C3%B3n%20sobre%20The%20Boat%20Playa%20del%20Carmen">
        9841642844
      </a>
    </nav>
    <!---->
    <div class="hidden navbar-menu relative z-50">
      <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
      <nav class="fixed top-0 left-0 bottom-0 flex flex-col w-5/6 max-w-sm py-6 px-6 bg-white border-r overflow-y-auto">
        <div class="flex items-center mb-8">
          <a class="mr-auto text-3xl font-bold leading-none" href="#">
            <img class="h-10" src="rara" alt="" width="auto">
          </a>
          <button class="navbar-close">
            <svg class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
            </svg>
          </button>
        </div>
        <div>
          <ul>
            <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded" href="#">Inicio</a></li>
            <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded" href="#">Desarrollos</a></li>
            <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded" href="#">Blog</a></li>
          </ul>
        </div>
      </nav>
    </div>

    <section class="bg-black skewed-bottom-right">
      <div class="bg-gray-50 pt-12 lg:pt-20 pb-20 radius-for-skewed" style="background: url(portada.png)">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap -mx-4">
            <div class="w-full lg:w-1/2 px-4 mb-12 md:mb-20 lg:mb-0 flex items-center">
              <div class="w-full text-center lg:text-left">
                <div class="max-w-md mx-auto lg:mx-0 mt-20">
                  <h2 class="mb-8 text-4xl lg:text-5xl font-bold font-heading">
                    <span>
                      Departamentos en venta
                    </span>
                    <span class="text-green-600">
                      Riviera Maya
                    </span>
                  </h2>
                </div>
              </div>
            </div>
            <div class="mx-auto lg:mx-0">
              <p class="text-base font-bold mb-6 text-white leading-loose m-8 mb-40">
                Ya sabes que inventir en la Riviera Maya es la mejor manera para hacer crecer tu dinero... Pero no te decides por la gran gran cantidad de desarrollos en preventa y departamentos, todos muy prometodores. Nuestro equipo de expertos puede ayudarte a encontrar la mejor opción para ti según tu presupuesto y lo que estás buscando, desde un departamento a pocos metros de la playa o un condominio rodeado de la hermosa naturaleza que ofrece Playa del Carmen. Tenemos convenios con desarrolladores inmobiliarios expertos, las mejores ubicaciones para la propiedad que buscas ya sea para vacacionar, rentar, invertir o vivir.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!--SLIDER DE IMEGENES-->
    <div class="slider">
      <div class="slide-track">
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Levitad</a>
          <img src="/SLIDERS/LEVITAD.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Centuria 15bis</a>
          <img src="/SLIDERS/slider1.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Musa del Carmen</a>
          <img src="/SLIDERS/Musa-del-carmen.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">The Yellow Condos</a>
          <img src="/SLIDERS/corazon-playa-fachada2-playa-del-carmen_gzdloi.jpg" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Meliora</a>
          <img src="/SLIDERS/meliora-patio-playa-del-carmen.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Ceiba 38</a>
          <img src="/SLIDERS/ceiba38-fachada-playa-del-carmen2.jpg" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Ibiza Residences</a>
          <img src="/SLIDERS/ibiza-residences-fachada-playa-del-carmen.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Kumarú</a>
          <img src="/SLIDERS/kumaru-fachada-playa-del-carmen.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Huaya</a>
          <img src="/SLIDERS/huaya-18-fachada-playa-del-carmen.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Mar y Miel</a>
          <img src="/SLIDERS/mar-y-miel-area-social-tulum2_ep75oj.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Solemn</a>
          <img src="/SLIDERS/Solemn-Posterior-Noche6-tulum_xi5jrw.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Hola</a>
          <img src="/SLIDERS/puerta-azul-fachada-dia-tulum2_mfckeo.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Phimai Tulum</a>
          <img src="/SLIDERS/pimahi-tulum-fachada-tulum2_jftizu.png" height="100" width="250" alt="">
        </div>
        <div class="slide">
          <a class="absolute text-white text-2xl font-bold m-2 mt-60" href="">Taanah</a>
          <img src="/SLIDERS/taanah-fachada2-tulum2_veeqfo.png" height="100" width="250" alt="">
        </div>
	    </div>
    </div>

    <!--Slider imagenes-->
    <div class="flex flex-col items-center">
      <div class="w-full bg-white rounded overflow-x-hidden flex snap-x" style="height: 85vh">
        <div class="snap-start w-full h-full flex items-center  text-white text-4xl font-bold flex-shrink-0 bg-black relative" id="slide-1">
          <img src="/Snap/bamoa-fachada-playa-del-carmen2.jpg" class="h-full w-full object-cover absolute inset-0 z-10 opacity-70">
          <h1 class="z-20 m-8">Bamoa </br> Playa del Carmen </br> $300,000 USD</h1> 
          <!--<a class="" href="#">IR A CATALOGO</a>-->
        </div>
        <div class="snap-start w-full h-full flex items-center text-white text-4xl font-bold flex-shrink-0 bg-black relative" id="slide-2">
          <img src="/Snap/centuria15-bis-fachada-noche-playa-del-carmen_u0dm7p-1_g91p1d.jpg" class="h-full w-full object-cover absolute inset-0 z-10 opacity-70">
          <h1 class="z-20 m-8">Centuria 15bis </br> Playa del Carmen </br> $150,000 USD</h1>
        </div>
        <div class="snap-start w-full h-full flex items-center text-white text-4xl font-bold flex-shrink-0 bg-black relative" id="slide-3">
          <img src="/Snap/ibiza-residences-fachada-playa-del-carmen.jpg" class="h-full w-full object-cover absolute inset-0 z-10 opacity-70">
          <h1 class="z-20 m-8">Ibiza Residences </br> Playa del Carmen </br> $400,000 USD</h1>
        </div>
        <div class="snap-start w-full h-full flex items-center text-white text-4xl font-bold flex-shrink-0 bg-black relative" id="slide-4">
          <img src="/Snap/huaya-18-fachada-playa-del-carmen.jpg" class="h-full w-full object-cover absolute inset-0 z-10 opacity-70">
          <h1 class="z-20 m-8">HUAYA 18 CONDOS </br> Playa del Carmen </br>$400,000 USD</h1>
        </div>
        <div class="snap-start w-full h-full flex items-center text-white text-4xl font-bold flex-shrink-0 bg-black relative" id="slide-5">
          <img src="/Snap/VillaAnunna.jpg" class="h-full w-full object-cover absolute inset-0 z-10 opacity-70">
          <h1 class="z-20 m-8">Villa Anunna </br> Tulum </br>$970,000 USD</h1>
        </div>
        <div class="snap-start w-full h-full flex items-center text-white text-4xl font-bold flex-shrink-0 bg-black relative" id="slide-6">
          <img src="/Snap/villa-niburu-entrada-tulum_xa5y8t.jpg" class="h-full w-full object-cover absolute inset-0 z-10 opacity-70">
          <h1 class="z-20 m-8">Villa Niburu </br> Tulum </br>$750,000 USD</h1>
        </div>
      </div>
      <div class="flex mt-4">
        <a class="w-8 mr-1 h-8 text-gray-700 rounded-full bg-white flex justify-center items-center" href="#slide-1">1</a>
        <a class="w-8 mr-1 h-8 text-gray-700 rounded-full bg-white flex justify-center items-center" href="#slide-2">2</a>
        <a class="w-8 mr-1 h-8 text-gray-700 rounded-full bg-white flex justify-center items-center" href="#slide-3">3</a>
        <a class="w-8 mr-1 h-8 text-gray-700 rounded-full bg-white flex justify-center items-center" href="#slide-4">4</a>
        <a class="w-8 h-8 text-gray-700 rounded-full bg-white flex justify-center items-center" href="#slide-5">5</a>
        <a class="w-8 h-8 text-gray-700 rounded-full bg-white flex justify-center items-center" href="#slide-6">6</a>
      </div>
    </div>


    <div class="bg-brand leading-loose grid grid-cols-1 sm:grid-cols-1 md:grid-cols-2 ">
      <div class="">
        <img class="m-4" src="Alejandra.png"> 
      </div>
      <div class="m-8">
        <h1 class="text-center text-lg font-bold m-2">
          ACERCA DE NOSOTROS
        </h1>
        <p class="text-gray-700 text-justify text-lg m-2">
          Somos la inmobiliaria de bienes raíces con el mayor listado de departamentos en preventa en Tulum, tenemos las mejores opciones de propiedades que se ajustan a tus necesidades al mejor precio, desde departamentos, oficinas, estudios, terrenos, casas todo disponible para comprar, invertir o rentar en el corazón de la Riviera Maya
        </p>
        <h2 class="text-center text-lg font-bold m-4">
          ¿Quieres hacer una inversión segura en Tulum?
        </h2>
        <p class="text-gray-700 text-justify text-lg m-2 ">
          Tenemos la solución perfecta, contamos con propiedades en los residenciales más seguros y en los desarrollos inmobiliarios de Tulum que ofrecen el mayor retorno de inversión y con la mejor plusvalía por sus ubicaciones al mejor precio. Ofrecemos gran variedad de inmuebles que se ajustan a tu presupuesto y necesidades. Definitivamente tenemos lo que estás buscando.
        </p>
      </div>
    </div>

    <!---->
    <div class="grid grid-cols-1 sm:grid-cols-1 md:grid-cols-2 bg-gray-700">
      <div class="w-full"  style="">
        <img class="mx-auto mt-20" src="agente.png"> 
          <div class="container mx-auto">
            <h1 class="font-bold text-white text-center text-4xl mt-10">
              CONTÁCTANOS
            </h1>
          </div>
          <div class="grid grid-cols-1 sm:grid-cols-1 md:grid-cols-2 flex m-8">
            <div class="text-white text-center">
              <p class="font-bold text-xl">
                Teléfono
              </p>
              <p class="text-lg">
                984 164-2844
              </p>
            </div>
            <div class="text-white text-center ">
              <p class="font-bold text-xl">
                Horarios
              </p>
              <p class="text-lg">
                9:00 am a 6:00 pm
                <br>
                Lunes - viernes
              </p>
            </div>
          </div>
      </div>
      <div class="w-full p-5 mt-12">
				<form class="px-8 pt-6 pb-8 mb-4 rounded">
					<div class="mb-4">
						<label class="block mb-2 text-sm font-bold text-white" placeholder="Username">
							Nombre
						</label>
							<input class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline" placeholder="Escribe tu nombre"/>
					</div>
					<div class="mb-4">
						<label class="block mb-2 text-sm font-bold text-white">
						  Email
						</label>
						<input class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border border-red-500 rounded shadow appearance-none focus:outline-none focus:shadow-outline" placeholder="Example@email.com"/>
					</div>
          <div class="mb-4">
						<label class="block mb-2 text-sm font-bold text-white">
							Teléfono
						</label>
						<input class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline" placeholder="Numero"/>
					</div>
          <div class="mb-4">
						<label class="block mb-2 text-sm font-bold text-white">
							Mensaje
						</label>
						<input class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline mb-3" placeholder="Escribir mensaje"/>
					</div>
					<div class="mb-6 text-center">
						<button class="w-full px-6 py-2 font-bold text-white bg-blue-500 rounded-full hover:bg-blue-700 focus:outline-none focus:shadow-outline" type="button">
							Enviar
						</button>
					</div>
					<hr class="mb-6 border-t"/>
				</form>
      </div>
    </div>

    <!--FOOTER-->
    <footer class="footer bg-gray-800 relative pt-1 border-b-2 border-blue-700">
      <div class="container mx-auto px-6">
        <div class="sm:flex sm:mt-8">
          <div class="mt-8 sm:mt-0 sm:w-full sm:px-8 flex flex-col md:flex-row justify-between">
            <div class="flex flex-col">
              <span class="font-bold text-blue-500 uppercase mb-2 text-xl">¿No encontraste lo que buscas?</span>
              <span class="my-2"><a href="#" class="text-white text-md hover:text-blue-300 underline">Ayuda en linea</a></span>
              <span class="font-bold text-blue-500 uppercase mb-2 text-xl">Contacta un broker</span>
              <span class="my-2"><a href="#" class="text-white text-md hover:text-blue-300 underline">Contactar</a></span>
              <span class="font-bold text-blue-500 uppercase mb-2 text-xl">¿DUDAS SOBRE INVERSIÓN?</span>
              <span class="my-2"><a href="#" class="text-white text-md hover:text-blue-300 underline">Solicitar llamada</a></span>
            </div>
            <div class="flex flex-col">
              <span class="font-bold text-blue-500 uppercase mt-4 md:mt-0 mb-2 text-xl">Datos de contacto</span>
              <span class="my-2 text-white text-md">Av. Calle 14 Nte 171, Gonzalo Guerrero, 77720 Playa del Carmen, <br> Quintana Rooo</span>
              <span class="my-2"><a href="#" class="text-white  text-md hover:text-blue-300 underline">Tel: +52 984 164 28 44</a></span>
              <span class="font-bold text-blue-500 uppercase mt-4 md:mt-0 mb-2 text-xl">HORARIO DE ATENCIÓN</span>
              <span class="my-2 text-white text-md">Lunes - Viernes 9:00 am a 6:00 pm</span> 
            </div>
            <div class="flex flex-col">
            <form class="container">
              <span class="font-bold text-blue-500 uppercase mt-4 md:mt-0 mb-2 text-xl">LO MAS NUEVO EN NEWSLETTER</span>
              <label class="block mb-2 text-sm font-bold text-white" placeholder="Username">
								Email
							</label>
							<input class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline" placeholder="Example@email.com"/>
              <div class="mb-6 text-center">
								<button class="mt-2 py-1 px-6 font-bold text-white bg-blue-500 rounded-full hover:bg-blue-700 focus:outline-none focus:shadow-outline" type="button">
									Enviar
								</button>
							</div>
            </form>
            <span class="font-bold text-blue-500 uppercase mt-4 md:mt-0 mb-2 text-xl">Redes sociales</span>
            <div class="flex sm:justify-center xl:justify-start mx-auto">
              <a href="https://www.facebook.com/theboatplayadelcarmen/" class="w-8 h-8">
                <img src="facebook.png">
              </a>
              <a href="https://www.instagram.com/theboatplayadelcarmen/" class="w-8 h-8">
                <img src="instagram.png">
              </a>
              <a href="https://web.whatsapp.com/send?phone=+529841642844&text=Estoy%20interesado%20en%20recibir%20m%C3%A1s%20informaci%C3%B3n%20sobre%20The%20Boat%20Playa%20del%20Carmen" class="w-8 h-8">
                <img src="whatsapp.png">
              </a>
              <a href="" class="w-8 h-8">
                <img src="skype.png">
              </a>
              <a href="" class="w-8 h-8">
                <img src="linkedin.png">
              </a>
            </div>
              <img class="flex mx-auto mt-6" src="playa_2.png">
            </div>
          </div>
        </div>
      </div>
      <div class="container mx-auto px-6">
        <div class="mt-16 border-t-2 border-gray-300 flex flex-col items-center">
          <div class="sm:w-2/3 text-center py-6">
            <img class="mx-auto h-10" src="logo-white2.png">
            <!--<p class="text-base text-white font-bold mb-2">
              &copy; 2021 — Capital 28
            </p>-->
          </div>
        </div>
      </div>
    </footer>

  </div>
</template>

<style>
	  .carousel{
      width: 100%;
      height: 560px;
      overflow: hidden;
  }

  .carousel ul{
      display: flex;
      animation: cambio 20s infinite
      alternate linear;
      width: 400%;

  }

  .carousel li{
      width: 100%;
      list-style: none;
  }

  .carousel img{
      width: 100%;
      /*height: 100%;*/

  }

  @keyframes cambio{
      0%{margin-left: 0;}
      20%{margin-left: 0;}

      25%{margin-left: -100%;}
      45%{margin-left: -100%;}

      50%{margin-left: -200%;}
      70%{margin-left: -200%;}

      75%{margin-left: -300%;}
      100%{margin-left: -300%;}
  }



    @-webkit-keyframes scroll {
  0% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
  100% {
    -webkit-transform: translateX(calc(-250px * 7));
            transform: translateX(calc(-250px * 7));
  }
}

@keyframes scroll {
  0% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
  100% {
    -webkit-transform: translateX(calc(-250px * 7));
            transform: translateX(calc(-250px * 7));
  }
}

.slider{
  background: white;
  /*box-shadow: 0 10px 20px -5px rgba(0, 0, 0, .125);*/
  height: 300px;
  margin: auto;
  padding: 10px;
  overflow: hidden;
  /*position: relative;*/
  width: 95%;
}

.slider::before, .slider::after{
  background: linear-gradient(to right, white 0%, rgba(255, 255, 255, 0) 100%);
  content: "";
  height: 300px;
  /*position: static;*/
  width: 100px;
  z-index: 2;
}

.slider::after{
  right: 0;
  top: 0;
  -webkit-transform: rotateZ(180deg);
          transform: rotateZ(180deg);
}

.slider::before{
  left: 0;
  top: 0;
}

.slider .slide-track {
  -webkit-animation: scroll 30s linear infinite;
          animation: scroll 30s linear infinite;
  display: flex;
  width: calc(250px * 14);
}

.slider .slide {
  height: 50px;
  width: 250px;
}

/*Slider3 */
.snap-x {
    scroll-snap-type: x mandatory;
    
  scroll-behavior: smooth;
  -webkit-overflow-scrolling: touch;
}
.snap-start {
  scroll-snap-align: start;
}
</style>
