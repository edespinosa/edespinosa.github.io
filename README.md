<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Edward Espinosa Hernández</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
  <style>
    body {
      background-color: #2c3e50;
      font-family: 'Roboto', sans-serif;
      color: #ecf0f1;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #3498db;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    nav {
      background-color: #2980b9;
      text-align: center;
      padding: 10px;
    }

    nav a {
      color: #ecf0f1;
      margin: 0 15px;
      text-decoration: none;
      font-size: 18px;
    }

    main {
      padding: 20px;
    }

    .servicios {
      background-color: #34495e;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .servicios h2 {
      color: #ecf0f1;
    }

    select {
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
    }

    .descripcion {
      margin-top: 10px;
    }

    .descripcion p {
      font-size: 16px;
    }

    .contacto {
      background-color: #2ecc71;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .contacto h2 {
      color: #ecf0f1;
    }

    .acerca-de {
      background-color: #e74c3c;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .acerca-de h2 {
      color: #ecf0f1;
    }

    .redes-sociales {
      margin-top: 20px;
      text-align: center;
    }

    .redes-sociales a {
      color: #ecf0f1;
      margin: 0 10px;
      font-size: 20px;
    }

    img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Edward Espinosa Hernández</h1>
    <p>Experto en soluciones digitales, seguridad informática e inteligencia artificial</p>
  </header>
  <nav>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contáctenos</a>
    <a href="#perfil">Perfil</a>
    <a href="#aporte-social">Aporte Social</a>
  </nav>
  <main>
    <section id="servicios" class="servicios">
      <h2>Servicios</h2>
      <label for="servicios">Selecciona un servicio:</label>
      <select id="servicios">
        <option value="desarrollo-web">Desarrollo web</option>
        <option value="seguridad-informatica">Seguridad informática</option>
        <option value="inteligencia-artificial">Inteligencia artificial</option>
      </select>
      <div class="descripcion">
        <p id="descripcion-servicio">Selecciona un servicio para ver la descripción.</p>
      </div>
    </section>
    <section id="contacto" class="contacto">
      <h2>Contacto</h2>
      <p>Teléfono: +57 300 555 5555</p>
      <p>Correo electrónico: edward.espinosa@example.com</p>
    </section>
    <section id="perfil" class="acerca-de">
      <h2>Perfil</h2>
      <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUVFRgWFRYYGBgZGBoYGBoYGBgZGhgaGBgZGhgYGBgcIS4lHB4rIRgYJjgmKy8xNTU1GiQ7QDs0Py40NTEBDAwMEA8QHhISHzErISs0NDQ0NDQ0NDQ0NDQxMTQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NP/AABEIAOEA4QMBIgACEQEDEQH/xAAcAAAABwEBAAAAAAAAAAAAAAAAAQIDBAUGBwj/xABFEAACAQIDBAcEBwUGBgMAAAABAgADEQQSIQUxQVEGImFxgZGhEzKx0UJSYnKSwfAHI1OCohQVFjPS4Rdjk7LC8SRDVP/EABoBAAMBAQEBAAAAAAAAAAAAAAECAwAEBQb/xAArEQACAgEDAwIGAgMAAAAAAAAAAQIRAxIhMQQTQTJRBRQiUnGRM2EVI4H/2gAMAwEAAhEDEQA/AKTA7YdLA9ZeR4dx4TQYTaKVNFNm+qdD4c4e0eitN+tSPs25b0PhvXw8pncbsytQPXQgcGGqn+YbvG0876o8l1Jo1gh2kDYntHRmY3QEAE7yeQ56SytHTtFYuxp3CgsdAASfCc2xr+2diBvJ0t26TadKMYEpZPpPoOxR7x/Lxmf2PgrsDaOtlYr3dD+B2GoTrDU+kgbT2IbHLa/685sgmki4tNIik0V7aaOc/wBjYcIzXpEbxNpXpK3CVGPwQNyJSMycsbRmieENGK6849XpZTIzyydkWqNX0f25pkfeoJB5gW39trzXK19dfGcpw9UowZfeUgjvBnSdmY8VURuLD1G8fHyiSiNFk+8K8TeC8AwZMIwXhGajAiHUHQxUBgaCmVb0yhuNV+HfJCPeSXW8rqtMobj3fh/tMgkoiIMStUWuTYSDjNqquidY8+HlGSsRuibVqqouxt+fdzlLjNqk3Cadv+/CRKzu5uxJiQsdRJuVjDKSbsbw7RwiDLHFsbgjmWCY1nU9g9I8NiSAr5H/AIb2Vifsnc/gb9kvnphrggEHQg7j3iefc81nRnpdiabpTL+0QkLlqXJUcSj+8PG403SDRQ6PjqaoqogCrqbDQfrfIVpIxNTO15m9qbYfJXWgpaorIiEAMFubu5vvIC5QLH3rxErdFPSit2uTVxJUa5QEHxPqfSXWEwuQC+/jMvsvFvSqM1RCzEXa3VZLnU5W0N+w3lqm31J3DtubEd4M0ovwNBrlly8g4x9DH6WKRxdSCJAxz8JOjoW5AcxhxeOM0bYzBZS7Qwt90p3pgTR4lhKXGpylYS8HPOK5RWtLzYGOZWVAbXYkd5XLbzIlIZM2SG9qmXfmB7rcZd8HN5OlqLcT4wyYhbhR3Rhnkio/7SLDXkBnikrQmsmmEYhKl43icUiC7Hw4wUCx6QMbtFE0vmPIfn8pW4raLvovVX1Pz/W+RFpgdp5mMoiuT8BVKrPf6Kk3sP1pG1S0ftBklEqEbGbQiI84AFzp2mWexejeKxljQpHIf/tqXSn3qSLv/KDCBspbSbsjY+IxTZcNSZ9bF/dpqftOdPDf2TqOwv2Y4anZsSxxD/VIyUgexBq38xIPKbimiU1CqFVVGiqAAAOSjcJhTjf/AAxx/wBfDfjf/RBOy/2gfVf8MExjybLrorhfaYlFO7Nc9w1PoJSCbX9n2Fuz1PqrlHe5+QMjLgvHk2mLchHYbwpI7+Ez2AOQezTV73dyLjORc+Uv8SpKEDfGcNhFRTYalixPad8gzpjwV2KwwNzbM54nie2ZnbNFlTNUCCzZRZsr+7mFgd4PxmtxzENc7+N/nM/0hUVBrraNF0xJR22MxhsW6NdXO/8AV5oqOMNRbNo3xmeo4XXXd+t8mpiRTcq3WQKOsNct9yuR+rER2tXAIycXuW2WR8Q9pDqbVUnQ6c4GxCtqDeT0svrTI2IqSE2pkivEYddY8Yk5ukNNhBYkwtjoTVAW3jy5X4R7H1OrlHH4R/othWaoHI6oup7Ta/yl3sjl5Zu6KHKLi3Ze/rGqtO8eOKUWDaX8oprHX1kbK7FVVQiMs9hcxeO2kqkqnXbs90ePGVTAsbub9g3R1Em2SHxxOiecimmSbscx7flFsbaCw0J17I7aOkK2NWhERxrCw4nRQASzHkqjUnumv2B0BxFcBqxOHTkQGqsOxTon81z9mMLZjgkl4fY9d9Qopp9eppcfYT3m8bDtnZNnbDw+EulGi13Q5qhzMTbgzHd3Cw5CYPHITdqjhd5Cg5mPIW/Pd2wO/BHLkceC96FdDcHkWu6+3qXIDVQCqlTvSn7o7zcjnN5nA0GvDTh5bhM3+z2pfCkfVqMPOx/OagKBCkNFtxTYgXO+wFtR298UtMDhK7aO3aFD36gzfVHWbyG7xtMhtTp+5utCmF+1U1Pgo0HiTCCU4x5Z0OCcg/xhjf4x/BT/ANMEwnficknUOhmFyYVTbV2L+A6o+BnMaSFmAGpJAHedBOzYegEREG5EVfIa+s5ps7oi2GkbBsI6YzUky6IeKQMNZTYjZpfdr2S7xB0tGaSm17EzDpFJR2A7gqqhSfpMAQvbv1MLpAiYeiKKbrdY8XY72bmZoHxWRb7pg9t4s1HLE6boY29gOKSszhAA/XhpCRyN0cccOXr3xDUeM6LRy00SqWKJNmlpSp6X7LyiVDulrSxgCFTo1rDk3+8MUrNKTrciYi7EAbybDvM3eCwiUaSICLgakfSY+8Zg0DXuBu5y3w+IqBbZz+uUEtxVsrZcY/GANbeeXGQGrO4sWIX6oMbRI4ohSFDRQN0dQQYdGd8iIzv9RBmOu6/BR2kgTc7J/Z67BXxNTIrHWnS1Ycg1U6DtCjxmBZhigZ1XKXc+4igu57lGvjNdszoFialjXcUF35Vs9XxPuJ/VNxsrYlHDrlo0gvAkau/aznrMe0ky7o02ZesbcgN9hzMwLKXY/R7C4PWmgDnQ1H69Rr8C51t2CwlzXxARqYOgdivc1sy38iPGO0qKqL2A5k/Myh6QbYpFU9m4d0qK9l6wst82o03EwoVui9xDuCAFuLFi3IrY5bduov6Tke3sP7LEVUG4OSv3W6y/0sJ1jOxbMGspUWQDM1ybhvs6aa3E510wwBSorXY5ww65BIKNlA0090pGRLN6bD6N9JRhaTJkzMz5hdrKNANdCeEj7S6UYitcFyi/VTqjxO8+JlIFh5ZrOR5pVVhlow6ySqwnSLZKUyNlgjuWCaxNbMt0SwntMTTHBTnPcmvxtOpMbmYn9neF/wAyoeACD+bU+gE2wnNLk+jitgmMj1XsLmSH3SuxQzaRSqG6tSQnqVAVKPlCm7KRcMOR5Rt6jUbqesm8X3gHh8ZX4vFcU+PwhSHskdIto3JAsLAabt8ylZeqTp3ce+O7Ydmym5vbXX0kCjVIBHO4110MpGKRKUm3Q1li8kUohiE1CsPRJYd8PE5S+gU5Tc6XBI4HmJIQWQt9kkH4Sqwx1lIo558lpSkpIWytnVq+lJC/At7qDvc6eAueybfZPQpF62JfP9hSUQd595/MDshYlmUweHeq2SkjOw3hdy/ec9VfEzV7L6FMetiXsP4dMkD+aobE/wAoXvM2mCwaIiqiqqAdUKAFA7ANJLZEAzPYAa3awA7SToItgbI2ztmpRQLRRUHJQBf7RPE9u+X1CmSrK2t7EAaAEa/LymWxnSvD09EvVb7Oi/jP5AxlukFV2RswRCyuAml1O9WY3J8Ld0ZRZPuR9zWYjGU6eruq6Xte7aclGpldQ6UK1RUWm1nNsxI5gXyi+ltb34bphce5VyouGR2BJ3kNuueOg9ZNw7sr03GmRgT3Gw8t8NUTeTcf6SYmt7Z6dVyRoVUXCdwHffWU2GcqxA3i9uM1nTfDgVKVUfSFj221HxMydRMj8wZrJZW1I6hsmoXpU/eKmmpzA5QSNCNOsDM90v2Wi4dSh6tNgbXvpUNib7/eC+ck9E8aTTNIi4S5LE2UAkaGw7T5GVHTXpAiKcNTtm0DqEyIq6MAL65rhTcaR4wlJ1FWymSUe03L2MplhFgJWPjWPIRssTvM7cfw3LL1UjyZZEiybFIO2RquMJ3CRgscyzvxfDMUfVbJSzMT7d+cEPJBOn5Dp/tE7jLzojhcmFTTVyXPcdF9BLq85Lh9sV1UAVXstsozEhbcgdPCWlHpTiWQXcEg+9lUE9+lreE+PcWfZI6BiKmkhOZXbIxj1Ez1GzFibaAWA03Dxk166gaxGiiVETaDgg7r2t3zI4y6ggHvEv8AH4hG0B1maxz3uL7jHiCTK1q1t8NXHCIK6wgtjpHSJXuSlTQmKp07xDVABviWxVhpGUQaiXXuVtcZQPO01vQPoxh6tL21VS7ZiArHqC32R72/6Vx2TCLiidDreb7oft5cPhMuQu2ckXNlGg3nfDFSexHNKMVbZscBRqWKqgC52ALblUaDIoGo5bhHalahS/zqmdx9Hee7IugH3plKmPxuJ3XRDwXqLbv95h5wqmz/AGSHO4zaZVHEHeRfU+Up2/dnJ37Wy/ZdY7pa26igUfWfrHwUaDxvM1jMbUqm9R2c8Mx0Hcu4eES0acgbzKxglwc08spBZ5oNksHQK30G/pOvzmbNQcJO2RirPlb3XBU9/D1j9mUlshccnqL/AG/72f66jxKWBPlaRkxN6dhrprr5yybDivhHVQc9FfaAkEaX6yD+Xh2CZrZ7aEXtrfw4ww6bWnb4LS2e/k220mOJwKVVzA0r3BFg3VUkjmAL687zFYimcocE9uu7WaTY236SYd6FZwqksoZSSwBvc5Qp01tv8JRoFYMFN11CndccCR4CXw4EpPUgZJRkk09zUdAsYRVysB+8Q+aH8wfSZbpq+bFMSLMFVW0t1luuvPRRr2yX0axDLVpsNyuM3PrdWw7NYP2gYXLjGbg4Vu7qi/redOGCh1P5RHNLVg/DMqBFqsMLFqs9ZHluQFWPKsNFjqJGRGUhvLBH8sEYXUc5Y9WP4Nur4xiuI5gzvHOfEH3S5Nf0ZxgKezJ1X3e1d/nLbGIGFj4dkwF2U3BIMmrtqsBYtm+8AfXfJuDu0UvYnNgxTfM5Nt4IOh7DKvaJGc5d0axu0Xf3reErnczKLElKh5miC0Z9pCLmUom5IW72jeaJJgWFIm3Y4h1HfNZsZv3Xc/5CZFN47xNJszVG+9+Urhjqkkc3VK8bNHX23Ube5G/3dN+/drK+pjCTIoWOUKDObIpY8lBY+QnpLDFcnm7vl2GMQ198eDXkvBbAxFQkLSa6sEcNZCrG2hViDpcE2GgNzLfD9DKzFczoFYOQyEuOqgZTwFmuLG/OPqxQ8oZRk+EZ5Y6hsbjfLbbuyEw4Qo7OCzo+YAWdLZstvom+l9dJVLLwqcdS4ElJwdM2+wHNXMgYqKiMCQATuFwL+ImPdCjup39ZT3i4/KSMDtJ6LZk32IHHf2SDXqlmLHeSSe8m5mx4XGT9jZc6lFe4yhkijiSosIxaLRCSABck2AG8nkJ1UvJyKTXBMw+Ndb5bC+/T4RzaWOeuwaoxZgLAngOQtw1k7BdFMXUNhTyffIX01I8pd4b9ndc+/Vpr90M/xCyEs/Twdtq/2VWPPNUk6MWqx1FnRcP+zukPfrO33Qq/HNLXD9DMGn0Cx+0zH0BAk5fEsMeLf/Bl8PzS5pHK1SSsPhmf3UZvuqT8J13D7Hw6e7Rpjtyi/na8mhQNALSMviv2x/bHXwlv1S/SORf3RX/g1PwN8oJ1+0ET/K5PtQ3+Ih9zPIdU3isObGGVguBPHPo63JgIMbcjtjHtQOMJsSO+YzkkE8juYb1iYhVJ3QkpSvgAFzDZLRwWGghAXms2kZIhgQzFKNIREgATR7EF0f7w+Ez1tBNF0dPVcdq/nL9N/IiPUr/Wza9FMLRZHaqqWR1Ys4B6oF8gGa4JP2WB1HKaOrtLD00VErICuSxXO4IXmtMAE7+qxtxvM/0Y2ZSrK5qKTZ1XQuMoKsSRlFr3Ue8QPGaUbFoo2X2CFQos7HNmu373RjvVQCG4XnRl063bZy470qqKMbcw6OxCu+WoKlOxIViaao4YuS4UWNgb6WGlpIodJqllp4fDMQLImbM7aKOqcoHWsrHuPZLxsXRokCk9NFJUsFKLYisgcacMpY93dD/vfCg9aqDmZXubsQUREs7LqWIz6gQKnxBsErXMkjCbdx9aowWsgRkvdQhUlmtmdwd7Gw1lYst+kNdKtYuhuhVABYjJlQKU11Nrb5WlZ62FJQW1f0eVml9b3v8AsKJyRwLBaXRByG8klbM0q0z9tf8AuEbAjmGNnU8mU+REWW8Whoy3R2pUK/rhyvyk5GvE0tVB7B8IsCfMM+jhGhUr9pbSWllBBYtfQX0ABOZrAkLwvbjJ8oNrUHvlopmIUmzXyknhnYELu9YBpNpbF1hq6uoZWDA8VIIvxFxHozhhZVBFiFFx4R6YZcAggggCePlzNuVj3An4Sbh9iYp/doVCOZQqPNrCauvQDcSPukqfSV9XZ1gWaqSBxe5t43gVeSjsgUuiGMYgZFUncGqUwT3KGJkHH7Iei2VmQsN6q4cr962gPZNngNq+xohMKiZ21qVXsxPJUUbh3+UYzU6iOMTSpq29alFFRweIYLZW8pm1ezDGL8oxIw/M6QO4Gg0EsMSaAJAFZuWYoo/pvDw+QvkFJdLlmZi1gN5tugG2XBVqI+o0MdZvaP1KZy7lVVO7mcovJD7OrWv7FwO1SoHnaYykiqihujlagyGzAA8r3PjaNmMAMnSaPosMxqDsU+pmavNL0P1ap9xT6n5yuD+RHP1PoZttj7Oz5gKjoMyKwU6MGzbx2W9ZoV6J0MyqXds2a37ymvu23DIb7zrfTQSm6PUarFxTcJoua6lr3aw3A237+EvHwWNJKmuNcvE2szBQRYbtbzsyt6qTSOLGlptqwqPRqg+qo+UCmdXJuGc572At1R6zN7fwK06oCKVVkRwpJbKWvdbnU7uPOaNdl4kFL4kK5uyLme+g6xXThcjzjOL6PVWLMaod82U5g4Y2ZVJuw1AzL38I+HLplcpWiWfFrjUY0zI+zMAp2mnp7CfNVV3VRSK3OVmBzbioUX5ecGK6MuhUMy9aotMGxt1lBDd3DwnYupx3Vnny6bJVpGYtCyS8obFZxWII/cglt/WsSCB+EmVZpy8MsZbJkJQnHdrkjZYpBHjTgVIzYEdswbXRDzVT6CIxVdksQpa99FBJ7NwsPGU2z+kuEWki1MRSRgihlZ1BByjQgyT/AIrwNr/2qj/1F+F58zJNSaPqItOKJdPGOxAFJhzLEgeBtfzAhnEVb6U779bgA8rX1kal0iw7KGVmZTuIViD42jn9+Uebfhb5STyRXlG1L3JQqPYErqRuGXQ8RcsLxS1GJHVIHEnLyO6zHjaRRtijzb8L/KFU23QUZmfKBxZWA9RMskXw0HVH3LHXn6QSt/xBhP8A9ND/AKqfOHH3G1I4bcKCWNzv5+AmZ2xialQ2COEG4ZTqeZtLrFVAW0is15HUdOgotl0WXrZGuewgCTMVjLKV4yydwFlHiCCTyivcolSI61BeLpvYll0YixOh9DGmo8jEqrdkNi8ljhqtVrKrurE2BTqk9mlo8calLMMzV6g3uzEqp5Lcn085UvUYbiR3SI1UWyqLHiZXHT5JZbT2H3xzkk3tfkAP94jENnGbiNG/IyMd/Pl2x9lyoRxJF/lGdCRbGLzT9Ctajj/l/Bh85lxNF0MciuQONNgfNY+L1L8k8+8H+DoexVqlmFIAmyswJA0RwRa5F9bacZolxmOFv3KEXa+UowNrkqSrmwB8b6dkzuyMf7By+XNdcpF7aEg33dkuqm30I6quGuTdshA94iwFrm59OM7skZOXCaPPxyiobtpja9I2JVmpozKLK3WuAQA3HebDXvkhOkxBP7u4LZyC7HrXUgi40AK7u2ZpAY8oluxjfg5n1GReS9TbgJZirAuiqxpuEN1PvDTS40tHMXt4PkupGSslRdQTZRqu7nfXtlGiRfsoexju6B351Vl3hts0qZYojHPUzPnynQgghLEa9Y7+cy9emMxy7rm199uF+2TcsbZJTFCMG2vJLLOU0k/BCNOAU5PUZdRv5xpxc3l7IaaMttjDP7ViEYggahSRu7JA9i31G/CflNvljVGupOUE3uRxtp27pyzwRbuzuj1UlFKuCi2LjXQMjV6lFRquVSwufeutj+UtaO0jfrbQcjspEc+LDu4SyCx1UHKRl0ON7uv0H5v+iEm0KgtbaCa7rp6HTSVm29o1myo+IWsnvdTQA8iOc0a0FO9V/CI8mCpneifgX5QR6HHF2kv0b5texgc8Ob/+wUv4dP8AAvyglexEPzi9jl9TAMgGdgW3mx0Ej5mX6UvA6kw7pyHlPn2fSIz9Z2Yan0kMU2vYWPHfb4y82pXULbiZSmoIUZjBqkb4tasQ+phFYRULquCJCqDW8dLGEVvHjsLJahK1Le6AO3efPhEO/wCvzjnsuUI4cxrRPRITTE0XQhM2Kt/y3/KUCoRwmi6AD/5yLzRx/QT+UeEqaYmSP0NG2FMk2AJPADUmKyEGxBB7RaT8EMtXkdQO8y2bEVFNmW68m/0toZ2ZOq7bSq0eM4LyZ9FiwsvVSnUBBphTuuFyEHmMuh8pVexIJB4G3lLYeojkTolOFcAppHCIpVgaW1CaRsrEMI6Y20dMVobaNlY9aDLG1C0R3U23xlEoggLYPvtxF95k0rGlwSZg1jmB33J37x3dkSS1NO+AV48DqEcxH1EbGFU6637z+cWmFF95/Xbvjag6SQix9BIww54Nbz+cep0nuOsLcf1abUgOLJEON+zfnBBqRtLOQpTfICW6xAPdfn2xANUcQZAw20WChcpYDTTXzkn+3gb9Ow7/ACnzriz61SVEXG1WzWbfIheOYmpmN7xm0KQGw1qRZeN2hEw0GwyYpYgRYmMhax4RtBHIjKxQdpN6PbSXDYynXcEqhOYLbMQyMul9OPpIQkbE77ww5J5l9J15NtYPEG9KsgYn3H6j35ANo3gTJyVqiaAsByOoPgdDOHAyy2ftvEUP8qq6j6t8yfga6+k6llaVPc86WBN2nR2qltAgaohPA2K+ikD0kRn485gsF07YWFamrjiyEo34TdT6TQYLpNhalv3mQ8qgyeGfVfWWxzguFRzTwT/Jd5oLxC6i41B3EG48CNIYM6ozT4OaUGuRcIiBTDjqQjiJtBlirwxDqF0icsUFiwIYWGwOIFWOosJBHUWazULRY+ixKLJCLBZqBlgjuWCCzaTzhUqudMxt5fCMlYZgG+eOfRBQBiICIB3TBHM4PfEkxFot2XgtvEmCjagBooMI1FbzoPDfNQVJj6uBD9rIxgBg0jLK0SvaxDteNXibzKNAlPUqDMKKgK6XjkggYYaC0IiYBLwW0KlI3pu6H7LEX7wND4zR4HptWXSoqVBzIyN+JdP6ZkQYYMZOuAOKfKOn4Hpdhn94tTPJxmX8S39QJe0KyOMyOrjmjBvhOKK0kUMQ6EMjMp4FSQfMSsc0kRl08XxsdmBilnNMF0wxKWzMHHJxc/iFj53mhwHTWi2lRGQ8166/kfQysc68nNLpZLg1yxayFgdo0av+XUR+wHreKnWThKxyJ8MjLHJcjiiPIIyskII+onpHUEkII0oj9MTWHSOZIIq0EFh0nmRhAYoxN55SPcHaqIFBViTxBWw7dYzAYbuTvhFApHGERzgMAN95/OYwM17AnQdkO/KJI/8AcNHtwB7xeYwYtY3vfha1vGFaDIbXtpzhFjMYUukFoZAB0ObwI+MC8gJgCbQGHlJ7oHAvpMYIGDNARBMYVaC0TeHmhACSsNiAtgfP85GgtMYk1lBuVHl8pFzQXMKYw4lUjcZe7P6WYmloKhZR9F+uP6tfWZ68O8wGrOj7P6fqdK1P+ZD/AOLfOavZvSDDVbBKqgn6L9RvDNv8Jw4NHEqkcZSOSSJywRZ6KWP05wTZvSLE0bZKrqOV7r+E3E1+yv2kuLCtTV+bIcjeW4+kpHN7kZdP7HU4Ji/+IuF+pV8l+cEfvIXsM4wIkwQTiR6DAYmCCEAIRggmMHCaCCYwBuh8IIJjAEUvGHBMAIwhBBMYVV3+UTBBMYEKCCYApYowQQmCiDvggmMCHBBMYEMQ4ITAEcpwQTGHIIIJjH//2Q==" alt="Edward Espinosa" />
      <p>Soy un apasionado por la tecnología y especialista en soluciones digitales. Con experiencia en desarrollo web, seguridad informática y el fascinante mundo de la inteligencia artificial, mi objetivo es brindar soluciones innovadoras y seguras para satisfacer las necesidades de mis clientes.</p>
    </section>
    <section id="aporte-social" class="aporte-social">
      <h2>Aporte Social</h2>
      <!-- Incluye aquí contenido relacionado con tu aporte social -->
    </section>
    <div class="redes-sociales">
      <a href="https://www.facebook.com/tu-facebook" target="_blank"><i class="fab fa-facebook"></i></a>
      <a href="https://wa.me/tunumerodewhatsapp" target="_blank"><i class="fab fa-whatsapp"></i></a>
    </div>
  </main>
  <footer>
    <p>Copyright &copy; 2023 Edward Espinosa Hernández</p>
  </footer>

  <script>
    document.getElementById("servicios").addEventListener("change", function() {
      var descripcionServicio = document.getElementById("descripcion-servicio");
      switch (this.value) {
        case "desarrollo-web":
          descripcionServicio.innerText = "Desarrollo de sitios web a medida con las últimas tecnologías.";
          break;
        case "seguridad-informatica":
          descripcionServicio.innerText = "Asesoramiento y implementación de medidas de seguridad informática.";
          break;
        case "inteligencia-artificial":
          descripcionServicio.innerText = "Desarrollo de soluciones basadas en inteligencia artificial y machine learning.";
          break;
        default:
          descripcionServicio.innerText = "Selecciona un servicio para ver la descripción.";
      }
    });
  </script>
</body>
</html>
