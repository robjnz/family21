<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-16 text-4xl text-blue-100">
        <span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Places To Visit In London
      </h1>
      <p class="ml-8 text-blue-100 text-2xl">
        A to z guide of whats on at London museums and country houses parks and
        gardens.
      </p>
      <br />

      <div class="grid sm:flex">
        <alexandra /><!--alexandra palace-->
        <apsley /><!--Apsley House-->
        <bankengland /><!--bank of england museum-->
      </div>
      <div class="grid sm:flex">
        <battersea /><!--Battersea Park-->
        <batterseazoo /><!--Battersea Park Children’s Zoo-->
        <bethune /><!--Bethune Nature reserve-->
      </div>
      <div class="grid sm:flex">
        <bexley /><!--bexleyWoods-->
        <british /><!--British Museum-->
        <ashby /><!--Ashby’s Bixton windmill-->
      </div>
      <div class="grid sm:flex">
        <brockwell /><!--Brockwell Park-->
        <brooklands /><!--Brooklands Museum-->
        <mews /><!--THE ROYAL MEWS-->
      </div>
      <div class="grid sm:flex">
        <gallery /><!--The Queens Gallery-->
        <buckingham /><!--Buckingham Palace-->
        <carlyle />
        <!--Carlyle's House -->
      </div>
      <div class="grid sm:flex">
        <dickens /><!--Charles Dickens-->
        <chingford /><!--Chingford Sky Trail-->
        <chislehurst /><!--Chislehurst Caves-->
      </div>
      <div class="grid sm:flex">
        <churchhouse /><!--Church House Gardens-->
        <clarence /><!--clarence House-->
        <clink /><!--Clink Prison Museum-->
        </div>
      <div class="grid sm:flex">
        <minster /><!--Croydon Minster-->
        <crystalV /><!--Crystal Palace Park-->
        <deen /><!--DEEN CITY FARM-->
        </div>
      <div class="grid sm:flex">
        <demorgan /><!--De Morgan Center-->
        <design /><!--Design Museum-->
        <down /><!--Down House-->
        </div>
      <div class="grid sm:flex">
        <docklands /><!--Docklands Museum-->
        <eastbury /><!--Eastbury Manor House-->
        <elizabeth /><!--Elizabeth's Hunting Lodge-->
        </div>
      <div class="grid sm:flex">
        <eltham /><!--Eltham Palace-->
        <epping /><!--Epping Forest-->
        <emery /><!--Emery Walker’s House-->
        </div>
      <div class="grid sm:flex">
        <fairlop /><!--Fairlop Waters Park-->
        <fenton /><!--fenton house-->
        <fleming /><!--Alexander Fleming Laboratory Museum-->
        </div>
      <div class="grid sm:flex">
        <forty /><!--forty hall-->
        <freud /><!--Freud Museum-->
        <geffrye /><!--Geffrye Museum-->
        </div>
      <div class="grid sm:flex">
        <hackney /><!--Hackney City Farm-->
        <hall /><!--Hall Place & Gardens-->
        <hampstead /><!--Hampstead Heath-->
        </div>
      <div class="grid sm:flex">
        <havering /><!--Havering Country Park-->
        <robinson /><!--HEATH ROBINSON MUSEUM-->
        <belfast /><!--HMS Belfast-->
        </div>
      <div class="grid sm:flex">
        <horniman /><!--Horniman Museam & Park-->
        <hospital /><!--Hospital Chapel Ilford-->
        <house /><!--House Mill-->
        </div>
      <div class="grid sm:flex">
        <war /><!--Imperial War Museum-->
        <jack /><!--Jack The Ripper Museum-->
        <jewish /><!--jewish museum-->
        </div>
      <div class="grid sm:flex">
        <keats /><!--Keats House -->
        <kenpalace /><!--Kensington Palace-->
        <kenwood /><!--kenwood house-->
        </div>
      <div class="grid sm:flex">
        <kew /><!--Kew Gardens -->
        <lee /><!--Lee Valley-->
        <canal /><!--London canal museum-->
        </div>
      <div class="grid sm:flex">
        <eye /><!--London Eye-->
        <mithraeum /><!--London Mithraeum-->
        <transport /><!--London Transport Museum -->
        </div>
      <div class="grid sm:flex">
        <zoo /><!--london zoo-->
        <tussauds /><!--madame tussauds-->
        <marblehouse /><!--MARBLE HILL HOUSE -->
        </div>
      <div class="grid sm:flex">
        <markfield /><!--Markfield -->
        <mayesbrook /><!--Mayesbrook Park-->
        <morden /><!--MORDEN HALL PARK-->
        </div>
      <div class="grid sm:flex">
        <mudchute /><!--mudchute-->
        <childhood /><!-- Museum of Childhood-->
        <museumlondon /><!--museum of london-->
        </div>
      <div class="grid sm:flex">
        <army /><!--National Army Museum-->
        <natural /><!-- Natural History Museum-->
        <newham /><!--Newham City Farm-->
        </div>
      <div class="grid sm:flex">
        <queen /><!--Queen Elizabeth Olympic Park-->
        <pitzhanger /><!--Pitzhanger Manor House-->
        <ragged /><!--Ragged School Museum-->
        </div>
      <div class="grid sm:flex">
        <rainham /><!--Rainham Hall-->
        <ranger /><!--Ranger’s House-->
        <red /><!--Red house-->
        </div>
      <div class="grid sm:flex">
        <regentscanal /><!--Regent’s Canal-->
        <regentspark /><!--Regent’s Park-->
        <roundwood /><!--Roundwood Park-->
        </div>
      <div class="grid sm:flex">
        <airforce /><!--Royal Air Force Museum-->
        <greenwich /><!--Royal Museums Greenwich-->
        <ruislip /><!--Ruislip Woods -->
        </div>
      <div class="grid sm:flex">
        <saatchi /><!--Saatchi Gallery-->
        <science /><!--Science Museum-->
        <serpentine /><!--Serpentine Galleries-->
        </div>
      <div class="grid sm:flex">
        <severndroog /><!--Severndroog Castle-->
        <homes /><!--Sherlock Holmes Museum-->
        <shirley /><!--Shirley Windmill-->
        </div>
      <div class="grid sm:flex">
        <shreksadventure /><!--shreksadventure-->
        <southwarkcath /><!--Southwark Cathedral-->
        <antioch /><!--St. Margaret of Antioch-->
        </div>
      <div class="grid sm:flex">
        <pauls /><!--St. Pauls Cathedral-->
        <stephens /><!--Stephens house-->
        <sutton /><!--Sutton House-->
        </div>
      <div class="grid sm:flex">
        <britain /><!--Tate Brittain-->
        <tate /><!--Tate Modern -->
        <thames /><!--Thames Barrier-->
        </div>
      <div class="grid sm:flex">
        <cartoon /><!--The Cartoon Museum-->
        <dungeon /><!--The London Dungeon-->
        <national /><!--the national Gallery-->
        </div>
      <div class="grid sm:flex">
        <operating /><!--The Old Operating Theatre-->
        <totteridge /><!--Totteridge fields-->
        <towerbridge /><!--Tower Bridge-->
        </div>
      <div class="grid sm:flex">
        <tower /><!--Tower Of London-->
        <trinity /><!--Trinity Buoy Wharf-->
        <upminster /><!--Upminster Windmill-->
        </div>
      <div class="grid sm:flex">
        <valence /><!--Valence House Museum-->
        <valentines /><!--Valentines Mansion-->
        <warrooms /><!--churchils War rooms-->
        </div>
      <div class="grid sm:flex">
        <victoriaalbert /><!--Victoria & Albert Museum-->
        <victoria /><!--Victoria Park-->
        <viktor /><!--Viktor Wyne Museum-->
        </div>
      <div class="grid sm:flex">
        <wandsworthcommon /><!--Wandsworth Common-->
        <wanstead /><!--Wansted Park-->
        <wellcome /><!--Wellcome Collection-->
        </div>
      <div class="grid sm:flex">
        <westminster /><!--Westminster Abbey-->
        <william /><!--William Morris Gallery-->
        <wimbledoncommon /><!--Wimbledon Common-->
        </div>
      <div class="grid sm:flex">
        <wimbledonmill /><!--Wimbledon Windmill-->
        </div>

      <div class="grid sm:flex">
        <book />
      </div>

      <br />
    </div>
  </Layout>
</template>

<script>
import antioch from "@/components/Visit/antioch";
import bexley from "@/components/Visit/bexley";
import chingford from "@/components/Visit/chingford";
import danson from "@/components/Visit/danson";
import docklands from "@/components/Visit/docklands";
import eastbury from "@/components/Visit/eastbury";
import elizabeth from "@/components/Visit/elizabeth";
import eltham from "@/components/Visit/eltham";
import epping from "@/components/Visit/epping";
import fairlop from "@/components/Visit/fairlop";
import greenwich from "@/components/Visit/greenwich";
import geffrye from "@/components/Visit/geffrye";
import hackney from "@/components/Visit/hackney";
import hall from "@/components/Visit/hall";
import havering from "@/components/Visit/havering";
import horniman from "@/components/Visit/horniman";
import hospital from "@/components/Visit/hospital";
import house from "@/components/Visit/house";
import jack from "@/components/Visit/jack";
import lee from "@/components/Visit/lee";
import mayesbrook from "@/components/Visit/mayesbrook";
import mudchute from "@/components/Visit/mudchute";
import newham from "@/components/Visit/newham";
import queen from "@/components/Visit/queen";
import ragged from "@/components/Visit/ragged";
import rainham from "@/components/Visit/rainham";
import ranger from "@/components/Visit/ranger";
import red from "@/components/Visit/red";
import severndroog from "@/components/Visit/severndroog";
import sutton from "@/components/Visit/sutton";
import thames from "@/components/Visit/thames";
import tower from "@/components/Visit/tower";
import trinity from "@/components/Visit/trinity";
import upminster from "@/components/Visit/upminster";
import valence from "@/components/Visit/valence";
import valentines from "@/components/Visit/valentines";
import victoria from "@/components/Visit/victoria";
import viktor from "@/components/Visit/viktor";
import wanstead from "@/components/Visit/wanstead";
import william from "@/components/Visit/william";
import alexandra from "@/components/Visit/alexandra";
import bethune from "@/components/Visit/bethune";
import canal from "@/components/Visit/canal";
import forty from "@/components/Visit/forty";
import jewish from "@/components/Visit/jewish";
import markfield from "@/components/Visit/markfield";
import stephens from "@/components/Visit/stephens";
import airforce from "@/components/Visit/airforce";
import totteridge from "@/components/Visit/totteridge";
import fenton from "@/components/Visit/fenton";
import zoo from "@/components/Visit/zoo";
import freud from "@/components/Visit/freud";
import down from "@/components/Visit/down";
import crystalV from "@/components/Visit/crystalV";
import chislehurst from "@/components/Visit/chislehurst";
import churchhouse from "@/components/Visit/churchhouse";
import shirley from "@/components/Visit/shirley";
import minster from "@/components/Visit/minster";
import morden from "@/components/Visit/morden";
import wimbledonmill from "@/components/Visit/wimbledonmill";
import deen from "@/components/Visit/deen";
import wimbledoncommon from "@/components/Visit/wimbledoncommon";
import wandsworthcommon from "@/components/Visit/wandsworthcommon";
import demorgan from "@/components/Visit/demorgan";
import batterseazoo from "@/components/Visit/batterseazoo";
import battersea from "@/components/Visit/battersea";
import roundwood from "@/components/Visit/roundwood";
import pitzhanger from "@/components/Visit/pitzhanger";
import emery from "@/components/Visit/emery";
import robinson from "@/components/Visit/robinson";
import ruislip from "@/components/Visit/ruislip";
import marblehouse from "@/components/Visit/marblehouse";
import kew from "@/components/Visit/kew";
import museumlondon from "@/components/Visit/museumlondon";
import bankengland from "@/components/Visit/bankengland";
import mithraeum from "@/components/Visit/mithraeum";
import pauls from "@/components/Visit/pauls";
import towerbridge from "@/components/Visit/towerbridge";
import british from "@/components/Visit/british";
import hampstead from "@/components/Visit/hampstead";
import kenwood from "@/components/Visit/kenwood";
import regentspark from "@/components/Visit/regentspark";
import keats from "@/components/Visit/keats";
import regentscanal from "@/components/Visit/regentscanal";
import victoriaalbert from "@/components/Visit/victoriaalbert";
import natural from "@/components/Visit/natural";
import science from "@/components/Visit/science";
import kenpalace from "@/components/Visit/kenpalace";
import design from "@/components/Visit/design";
import serpentine from "@/components/Visit/serpentine";
import saatchi from "@/components/Visit/saatchi";
import army from "@/components/Visit/army";
import carlyle from "@/components/Visit/carlyle";
import brockwell from "@/components/Visit/brockwell";
import ashby from "@/components/Visit/ashby";
import tate from "@/components/Visit/tate";
import southwarkcath from "@/components/Visit/southwarkcath";
import war from "@/components/Visit/war";
import belfast from "@/components/Visit/belfast";
import operating from "@/components/Visit/operating";
import clink from "@/components/Visit/clink";
import warrooms from "@/components/Visit/warrooms";
import britain from "@/components/Visit/britain";
import national from "@/components/Visit/national";
import westminster from "@/components/Visit/westminster";
import buckingham from "@/components/Visit/buckingham";
import mews from "@/components/Visit/mews";
import gallery from "@/components/Visit/gallery";
import clarence from "@/components/Visit/clarence";
import tussauds from "@/components/Visit/tussauds";
import dickens from "@/components/Visit/dickens";
import homes from "@/components/Visit/homes";
import wellcome from "@/components/Visit/wellcome";
import cartoon from "@/components/Visit/cartoon";
import fleming from "@/components/Visit/fleming";
import apsley from "@/components/Visit/apsley";
import brooklands from "@/components/Visit/brooklands";
import transport from "@/components/Visit/transport";
import eye from "@/components/Visit/eye";
import shreksadventure from "@/components/Visit/shreksadventure";
import dungeon from "@/components/Visit/dungeon";
import childhood from "@/components/Visit/childhood";


import book from "@/components/amazon/book";

import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Visit",
    meta: [
      {
        name: "description",
        content:
          " A to z guide of whats on at London museums and country houses parks and gardens.",
      },
    ],
  },
  components: {
    antioch,
    bexley,
    chingford,
    danson,
    docklands,
    eastbury,
    elizabeth,
    eltham,
    epping,
    fairlop,
    greenwich,
    geffrye,
    hackney,
    hall,
    havering,
    horniman,
    hospital,
    house,
    jack,
    lee,
    mayesbrook,
    mudchute,
    newham,
    queen,
    ragged,
    rainham,
    ranger,
    red,
    severndroog,
    sutton,
    thames,
    tower,
    trinity,
    upminster,
    valence,
    valentines,
    victoria,
    viktor,
    wanstead,
    william,
    alexandra,
    bethune,
    canal,
    forty,
    jewish,
    markfield,
    stephens,
    totteridge,
    airforce,
    fenton,
    zoo,
    freud,
    down,
    crystalV,
    chislehurst,
    churchhouse,
    shirley,
    minster,
    morden,
    wimbledonmill,
    deen,
    wimbledoncommon,
    wandsworthcommon,
    demorgan,
    batterseazoo,
    battersea,
    roundwood,
    pitzhanger,
    emery,
    robinson,
    ruislip,
    marblehouse,
    kew,
    museumlondon,
    bankengland,
    mithraeum,
    pauls,
    towerbridge,
    british,
    hampstead,
    kenwood,
    regentspark,
    keats,
    regentscanal,
    victoriaalbert,
    natural,
    science,
    kenpalace,
    design,
    serpentine,
    saatchi,
    army,
    carlyle,
    brockwell,
    ashby,
    tate,
    southwarkcath,
    war,
    belfast,
    operating,
    clink,
    warrooms,
    britain,
    national,
    westminster,
    buckingham,
    mews,
    gallery,
    clarence,
    tussauds,
    dickens,
    homes,
    wellcome,
    cartoon,
    fleming,
    apsley,
    brooklands,
    transport,
    date,
    eye,
    shreksadventure,
    dungeon,
    childhood,

    book,
  },
};
</script>
