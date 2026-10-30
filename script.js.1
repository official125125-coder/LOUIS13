/* =========================================
   LOUIS13
   ROYAL GAME PRESTIGE
========================================= */


/* =========================================
   CUSTOMER SERVICE
========================================= */

const whatsappCSLink =
  "https://joinlouis.wasap.my";

const telegramCSLink =
  "https://t.me/Louis13_Admin";


/* =========================================
   GROUP CHANNEL
========================================= */

const whatsappChannelLink =
  "https://joinlouis.wasap.my";

const telegramChannelLink =
  "https://t.me/Louis13_Channel";


/* =========================================
   GAME LIST

   Logo disimpan dalam folder:
   image/

   Jika PNG belum ada,
   logo default otomatis tampil.
========================================= */

const games = [

  {
    name: "918KissOri",
    logo: "image/918kissori.png",
    short: "918"
  },

  {
    name: "918Kaya",
    logo: "image/918kaya.png",
    short: "9K"
  },

  {
    name: "Mega888",
    logo: "image/mega888.png",
    short: "M8"
  },

  {
    name: "Pussy888",
    logo: "image/pussy888.png",
    short: "P8"
  },

  {
    name: "Evo888",
    logo: "image/evo888.png",
    short: "EVO"
  },

  {
    name: "XE88",
    logo: "image/xe88.png",
    short: "XE"
  },

  {
    name: "Newtown",
    logo: "image/newtown.png",
    short: "NT"
  },

  {
    name: "Joker",
    logo: "image/joker.png",
    short: "JK"
  },

  {
    name: "Suncity",
    logo: "image/suncity.png",
    short: "SC"
  },

  {
    name: "Lion King",
    logo: "image/lionking.png",
    short: "LK"
  },

  {
    name: "Live22",
    logo: "image/live22.png",
    short: "L22"
  },

  {
    name: "Ace333",
    logo: "image/ace333.png",
    short: "A3"
  },

  {
    name: "LPE",
    logo: "image/lpe.png",
    short: "LPE"
  },

  {
    name: "GW99",
    logo: "image/gw99.png",
    short: "GW"
  },

  {
    name: "ROLLEX",
    logo: "image/rollex.png",
    short: "RX"
  },

  {
    name: "PLAYBOY",
    logo: "image/playboy.png",
    short: "PB"
  },

  {
    name: "KING855",
    logo: "image/king855.png",
    short: "K855"
  },

  {
    name: "3WIN8",
    logo: "image/3win8.png",
    short: "3W"
  },

  {
    name: "Slots22",
    logo: "image/slots22.png",
    short: "S22"
  }

];


/* =========================================
   ELEMENTS
========================================= */

const gameGrid =
  document.getElementById("gameGrid");

const popup =
  document.getElementById("gamePopup");

const popupClose =
  document.getElementById("popupClose");

const popupGameName =
  document.getElementById("popupGameName");

const popupGameLogo =
  document.getElementById("popupGameLogo");

const popupWhatsapp =
  document.getElementById("popupWhatsapp");

const popupTelegram =
  document.getElementById("popupTelegram");

const whatsappChannel =
  document.getElementById("whatsappChannel");

const telegramChannel =
  document.getElementById("telegramChannel");


/* =========================================
   SET ALL LINKS
========================================= */

popupWhatsapp.href =
  whatsappCSLink;

popupTelegram.href =
  telegramCSLink;

whatsappChannel.href =
  whatsappChannelLink;

telegramChannel.href =
  telegramChannelLink;


/* =========================================
   LOGO CACHE
========================================= */

const logoCache =
  new Map();


/* =========================================
   DEFAULT LOGO
========================================= */

function createDefaultLogo(shortName) {

  const logo =
    document.createElement("div");

  logo.className =
    "default-game-logo";

  logo.textContent =
    shortName;

  return logo;

}


/* =========================================
   PRELOAD LOGO
========================================= */

function preloadLogo(game) {

  return new Promise((resolve) => {

    const image =
      new Image();


    image.onload =
      function () {

        logoCache.set(
          game.name,
          {
            available: true,
            src: game.logo
          }
        );

        resolve();

      };


    image.onerror =
      function () {

        logoCache.set(
          game.name,
          {
            available: false,
            src: null
          }
        );

        resolve();

      };


    image.src =
      game.logo;

  });

}


/* =========================================
   PRELOAD ALL LOGOS
========================================= */

function preloadAllLogos() {

  games.forEach((game) => {

    preloadLogo(game).then(() => {

      updateGameCardLogo(game);

    });

  });

}


/* =========================================
   CREATE GAME LOGO
========================================= */

function createCardLogo(game) {

  const wrapper =
    document.createElement("div");

  wrapper.className =
    "game-logo-wrap";

  wrapper.dataset.logoFor =
    game.name;


  const cached =
    logoCache.get(game.name);


  if (
    cached &&
    cached.available
  ) {

    const image =
      document.createElement("img");

    image.className =
      "game-logo-img";

    image.src =
      cached.src;

    image.alt =
      game.name;

    wrapper.appendChild(image);

  }

  else {

    wrapper.appendChild(
      createDefaultLogo(
        game.short
      )
    );

  }


  return wrapper;

}


/* =========================================
   UPDATE GAME LOGO
========================================= */

function updateGameCardLogo(game) {

  const wrapper =
    document.querySelector(
      `[data-logo-for="${game.name}"]`
    );


  if (!wrapper) {
    return;
  }


  const cached =
    logoCache.get(game.name);


  if (
    !cached ||
    !cached.available
  ) {
    return;
  }


  const image =
    document.createElement("img");

  image.className =
    "game-logo-img";

  image.src =
    cached.src;

  image.alt =
    game.name;


  wrapper.replaceChildren(
    image
  );

}


/* =========================================
   CREATE GAME LIST
========================================= */

function loadGames() {

  gameGrid.innerHTML = "";


  games.forEach((game) => {

    const card =
      document.createElement("button");


    card.className =
      "game-card";

    card.type =
      "button";


    /* LOGO */

    const logo =
      createCardLogo(game);


    /* NAME */

    const name =
      document.createElement("strong");

    name.textContent =
      game.name.toUpperCase();


    /* PLAY */

    const play =
      document.createElement("small");

    play.textContent =
      "PLAY NOW";


    card.appendChild(logo);
    card.appendChild(name);
    card.appendChild(play);


    /* CLICK GAME */

    card.addEventListener(
      "click",
      () => {

        openGamePopup(game);

      }
    );


    gameGrid.appendChild(
      card
    );

  });

}


/* =========================================
   PREPARE POPUP LOGO
========================================= */

function preparePopupLogo(game) {

  popupGameLogo.innerHTML =
    "";


  const cached =
    logoCache.get(game.name);


  if (
    cached &&
    cached.available
  ) {

    const image =
      document.createElement("img");


    image.src =
      cached.src;

    image.alt =
      game.name;


    popupGameLogo.appendChild(
      image
    );

  }

  else {

    popupGameLogo.appendChild(
      createDefaultLogo(
        game.short
      )
    );

  }

}


/* =========================================
   OPEN POPUP
========================================= */

function openGamePopup(game) {

  /*
    Semua isi popup disiapkan
    terlebih dahulu.

    Selepas itu popup baru muncul.
    Ini mengurangkan efek kedip.
  */

  popupGameName.textContent =
    game.name;


  preparePopupLogo(game);


  requestAnimationFrame(() => {

    requestAnimationFrame(() => {

      popup.classList.add(
        "active"
      );


      popup.setAttribute(
        "aria-hidden",
        "false"
      );


      document.body.classList.add(
        "popup-open"
      );

    });

  });

}


/* =========================================
   CLOSE POPUP
========================================= */

function closePopup() {

  popup.classList.remove(
    "active"
  );


  popup.setAttribute(
    "aria-hidden",
    "true"
  );


  document.body.classList.remove(
    "popup-open"
  );

}


/* CLOSE BUTTON */

popupClose.addEventListener(
  "click",
  closePopup
);


/* CLICK OUTSIDE POPUP */

popup.addEventListener(
  "click",
  (event) => {

    if (
      event.target === popup
    ) {

      closePopup();

    }

  }
);


/* ESC */

document.addEventListener(
  "keydown",
  (event) => {

    if (
      event.key === "Escape" &&
      popup.classList.contains("active")
    ) {

      closePopup();

    }

  }
);


/* =========================================
   PARTICLES
========================================= */

const particlesContainer =
  document.getElementById(
    "particles"
  );


function createParticles() {

  if (!particlesContainer) {
    return;
  }


  const total =
    window.innerWidth <= 600
      ? 14
      : 25;


  for (
    let i = 0;
    i < total;
    i++
  ) {

    const particle =
      document.createElement("span");


    particle.className =
      "particle";


    particle.style.left =
      Math.random() * 100 + "%";


    particle.style.animationDuration =
      8 +
      Math.random() * 12 +
      "s";


    particle.style.animationDelay =
      Math.random() * 12 +
      "s";


    const size =
      1 +
      Math.random() * 2;


    particle.style.width =
      size + "px";

    particle.style.height =
      size + "px";


    particlesContainer.appendChild(
      particle
    );

  }

}


/* =========================================
   START WEBSITE
========================================= */

loadGames();

preloadAllLogos();

createParticles();


console.log(
  "LOUIS13 | Royal Game Prestige"
);
