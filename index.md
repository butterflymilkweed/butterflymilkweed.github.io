<html>
    <head>
    <style type="text/css">
body {
  
  margin: 0;
  padding: 1em;
}

position: fixed;

.centered {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}



.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: auto;
  grid-gap: 5px;
  
}



.item-a {
  grid-column: 2 / 3;
  grid-row: 1 / 2;
  justify-self: center;
}

.item-b {
  grid-column: 2 / 3;
  grid-row: 2 / 3;
  justify-self: center;
  text-align: center;
  font: 14px, Courier New;

}

.item-c {
  grid-column: 2 / 3;
  grid-row: 3 / 4;
  justify-self: center;
  text-align: center;

}


button {
    
  position: static; 
  background-color:  #32b1a9; 
  border: none;
  padding: 0.3em;
  color: #fadcd1;
  display: inline-block;
  font: 14px Courier New;

  -webkit-transition: 0.5s;

}

button:hover {
  background-color: #a58caf;   
  -webkit-transition: 0.5s;

}

#face {
  height: 35vw;
  -webkit-transition: 0.5s;
  

}

{card:"",
  desc:"",
  src:""}
        // CSS Content
        </style>
</head>
    <body>
<html>

<div class="container">
<div class="item-a">
<div class="item-b">
    </body>
    </head>
  
  <img id="face" src="https://i.ibb.co/bLfPRWG/Modern-Witch-Tarot-Deck-by-Lisa-Sterle.jpg">
  
  </div>
  
<div id="card" class="item-b">
  <p></p>
  </div>
  
  

<div style="text-align:center">
<button style="height:40px; width:150px;"
 <button type="button" id="button" class="button" onclick="buttonClick()">   <b>today's draw</b>	</button>
<p></p>
<div style="text-align:center">
<button style="height:40px; width:150px;"
  <button onclick=location.reload();
>  <b>reset deck</b>	
</button>



  

  </div>
  
  </div>
        <script language="JavaScript"  type="text/javascript">
// An array of cards

var cards = 
[
  {card: "The Fool",
desc: "a fresh start",
src: "https://live.staticflickr.com/65535/51704029507_a6a9f18453_m.jpg"},
{card: "The Magician",
desc: "pure energy",
src: "https://live.staticflickr.com/65535/51704822971_b6d36cc38d_m.jpg"},
{card: "The High Priestess",
desc: "intuition",
src: "https://live.staticflickr.com/65535/51705718425_744e718cf6_m.jpg"},
{card: "The Empress",
desc: "fertility",
src: "https://live.staticflickr.com/65535/51705718780_f8398d9b1a_m.jpg"},
{card: "The Emperor",
desc: "power",
src: "https://live.staticflickr.com/65535/51705504554_32e8a79c15_m.jpg"},
{card: "The Hierophant",
desc: "tradition",
src: "https://live.staticflickr.com/65535/51705504604_2b8a3bf08f_m.jpg"},
{card: "The Lovers",
desc: "harmony",
src: "https://live.staticflickr.com/65535/51705503989_750fd49775_m.jpg"},
{card: "The Chariot",
desc: "willpower",
src: "https://live.staticflickr.com/65535/51704036307_13c5914e69_m.jpg"},
{card: "Strength",
desc: "compassion",
src: "https://live.staticflickr.com/65535/51705504464_ee964c3e2d_m.jpg"},
{card: "The Hermit",
desc: "contemplation",
src: "https://live.staticflickr.com/65535/51704036357_fd365491a0_m.jpg"},
{card: "Wheel of Fortune",
desc: "karma",
src: "https://live.staticflickr.com/65535/51704035687_ea83f70fff_m.jpg"},
{card: "Justice",
desc: "fairness",
src: "https://live.staticflickr.com/65535/51704829371_cc7633bc36_m.jpg"},
{card: "The Hanged One",
desc: "sacrifice",
src: "https://live.staticflickr.com/65535/51705504584_c3491cf39f_m.jpg"},
{card: "Death",
desc: "changes",
src: "https://live.staticflickr.com/65535/51704829286_a555799550_m.jpg"},
{card: "Temperance",
desc: "calmness",
src: "https://live.staticflickr.com/65535/51705504509_8af52200fa_m.jpg"},
{card: "The Devil",
desc: "addiction",
src: "https://live.staticflickr.com/65535/51705718775_aca4c960c3_m.jpg"},
{card: "The Tower",
desc: "revolution",
src: "https://live.staticflickr.com/65535/51705718305_4c3155f536_m.jpg"},
{card: "The Star",
desc: "hope",
src: "https://live.staticflickr.com/65535/51705503954_13941fdeff_m.jpg"},
{card: "The Moon",
desc: "the unconscious",
src: "https://live.staticflickr.com/65535/51705718320_9f13e339c2_m.jpg"},
{card: "The Sun",
desc: "happiness",
src: "https://live.staticflickr.com/65535/51705503939_fea4d50bc4_m.jpg"},
{card: "Judgement",
desc: "rebirth",
src: "https://live.staticflickr.com/65535/51704036057_ecdfb85bd2_m.jpg"},
 {card: "The World",
desc: "completion",
src: "https://live.staticflickr.com/65535/51704829131_cd40d613bb_m.jpg"},
  {card:"Ace of Wands",
  desc:"creativity",
src:"https://live.staticflickr.com/65535/51704035932_213d468f39_m.jpg"},
  {card:"Two of Wands",
  desc:"planning", 
  src:"https://live.staticflickr.com/65535/51705718230_5b08041e88_m.jpg"},
  {card:"Three of Wands",
 desc:"expansion", 
 src:"https://live.staticflickr.com/65535/51705718255_a2e1d6206e_m.jpg"},
  {card:"Four of Wands",
  desc:"celebration",  src:"https://live.staticflickr.com/65535/51705504194_ae3df324c2_m.jpg"},
  {card:"Five of Wands",
  desc:"conflict", 
  src:"https://live.staticflickr.com/65535/51705718500_106396cca1_m.jpg"},
  {card:"Six of Wands",
  desc:"victory", 
  src:"https://live.staticflickr.com/65535/51705504444_a3ca82d8d4_m.jpg"},
  {card:"Seven of Wands",
  desc:"defense", 
  src:"https://live.staticflickr.com/65535/51705111583_66fc70903e_m.jpg"},
  {card:"Eight of Wands",
  desc:"swift action", 
  src:"https://live.staticflickr.com/65535/51704035992_4d197e4889_m.jpg"},
  {card:"Nine of Wands",
  desc:"hyper-awareness",
src:"https://live.staticflickr.com/65535/51705111513_eef360ba54_m.jpg"},
  {card:"Ten of Wands",
  desc:"burden",
src:"https://live.staticflickr.com/65535/51704036292_24cc59d62c_m.jpg"},
  {card:"Page of Wands",
  desc:"curiosity",  
  src:"https://live.staticflickr.com/65535/51704036147_e36857b693_m.jpg"},
  {card:"Knight of Wands",
  desc:"adventure", 
  src:"https://live.staticflickr.com/65535/51704829396_aefd21087d_m.jpg"},
  {card:"Queen of Wands",
  desc:"self-esteem", 
  src:"https://live.staticflickr.com/65535/51705111543_1137140334_m.jpg"},
  {card:"King of Wands",
  desc:"being a visionary", 
  src:"https://live.staticflickr.com/65535/51705718550_68763984aa_m.jpg"},
  {card:"Ace of Swords",
  desc:"Intellect", 
  src:"https://live.staticflickr.com/65535/51705504109_80442e44d2_m.jpg"},
  {card:"Two of Swords",
  desc:"being in a stalemate", 
  src:"https://live.staticflickr.com/65535/51704829106_229f6c7783_m.jpg"},
  {card:"Three of Swords",
  desc:"heartache", 
  src:"https://live.staticflickr.com/65535/51705503879_22674cc860_m.jpg"},
  {card:"Four of Swords",
  desc:"restoration", 
  src:"https://live.staticflickr.com/65535/51705504184_76b41bdf0f_m.jpg"},
  {card:"Five of Swords",
  desc:"competition", 
  src:"https://live.staticflickr.com/65535/51705111388_c0cde07be9_m.jpg"},
  {card:"Six of Swords",
  desc:"transition", 
  src:"https://live.staticflickr.com/65535/51705111603_2f14f2c02e_m.jpg"},
  {card:"Seven of Swords",
  desc:"deceit", 
  src:"https://live.staticflickr.com/65535/51705111578_9a70ca4da3_m.jpg"},
  {card:"Eight of Swords",
  desc:"victimization", 
  src:"https://live.staticflickr.com/65535/51704829321_8ea6722b30_m.jpg"},
  {card:"Nine of Swords",
  desc:"worry", 
  src:"https://live.staticflickr.com/65535/51705504309_7aa9c5d2f8_m.jpg"},
  {card:"Ten of Swords",
  desc:"deep wounds", 
  src:"https://live.staticflickr.com/65535/51705718750_a3f9b62c0a_m.jpg"},
  {card:"Page of Swords",
  desc:"new ideas", 
  src:"https://live.staticflickr.com/65535/51705718605_8a80cd0f5c_m.jpg"},
  {card:"Knight of Swords",
  desc:"aggression", 
  src:"https://live.staticflickr.com/65535/51705504269_224b936204_m.jpg"},
  {card:"Queen of Swords",
  desc:"being analytical", 
  src:"https://live.staticflickr.com/65535/51705504349_749565dbbf_m.jpg"},
  {card:"King of Swords",
  desc:"forthrightness", 
  src:"https://live.staticflickr.com/65535/51705504219_94b8203be1_m.jpg"},
  {card:"Ace of Pentacles",
  desc:"opportunities", 
  src:"https://live.staticflickr.com/65535/51704035917_2776e1b281_m.jpg"},
  {card:"Two of Pentacles",
  desc:"balancing", 
  src:"https://live.staticflickr.com/65535/51704035727_36d2f7fca8_m.jpg"},
  {card:"Three of Pentacles",
  desc:"teamwork", 
  src:"https://live.staticflickr.com/65535/51705718275_ed25b64ac2_m.jpg"},
  {card:"Four of Pentacles",
  desc:"resources", 
  src:"https://live.staticflickr.com/65535/51704829346_5138167747_m.jpg"},
  {card:"Five of Pentacles",
  desc:"struggle", 
  src:"https://live.staticflickr.com/65535/51704829331_a22f6515ae_m.jpg"},
  {card:"Six of Pentacles",
  desc:"giving", 
  src:"https://live.staticflickr.com/65535/51705718690_db0626c135_m.jpg"},
  {card:"Seven of Pentacles",
  desc:"waiting", 
  src:"https://live.staticflickr.com/65535/51704036212_45e3f27173_m.jpg"},
  {card:"Eight of Pentacles",
  desc:"hard work", 
  src:"https://live.staticflickr.com/65535/51704035977_f0dfd49217_m.jpg"},
  {card:"Nine of Pentacles",
  desc:"comfort", 
  src:"https://live.staticflickr.com/65535/51705504299_ecf0c97101_m.jpg"},
  {card:"Ten of Pentacles",
  desc:"legacy", 
  src:"https://live.staticflickr.com/65535/51705111648_8eab97e49b_m.jpg"},
  {card:"Page of Pentacles",
  desc:"being a beginner", 
  src:"https://live.staticflickr.com/65535/51705504319_fcd611c08f_m.jpg"},
  {card:"Knight of Pentacles",
  desc:"analytical thinking", 
  src:"https://live.staticflickr.com/65535/51705504254_4a54c1ac4c_m.jpg"},
  {card:"Queen of Pentacles",
  desc:"abundance", 
  src:"https://live.staticflickr.com/65535/51704829456_ce38b11694_m.jpg"},
  {card:"King of Pentacles",
  desc:"accumulation", 
  src:"https://live.staticflickr.com/65535/51704829381_f6e0922100_m.jpg"},
  {card:"Ace of Cups",
  desc:"new love", 
  src:"https://live.staticflickr.com/65535/51704829246_bb33865025_m.jpg"},
  {card:"Two of Cups",
  desc:"relationships", 
  src:"https://live.staticflickr.com/65535/51705718250_75691f35ab_m.jpg"},
  {card:"Three of Cups",
  desc:"friendship", 
  src:"https://live.staticflickr.com/65535/51704035767_1b86d8b770_m.jpg"},
  {card:"Four of Cups",
  desc:"apathy", 
  src:"https://live.staticflickr.com/65535/51704829341_ef8d218475_m.jpg"},
  {card:"Five of Cups",
  desc:"sadness", 
  src:"https://live.staticflickr.com/65535/51704036007_025a9dbd19_m.jpg"},
  {card:"Six of Cups",
  desc:"nostalgia", 
  src:"https://live.staticflickr.com/65535/51705718680_666e712557_m.jpg"},
  {card:"Seven of Cups",
  desc:"delusions", 
  src:"https://live.staticflickr.com/65535/51705718635_2b405bde9d_m.jpg"},
  {card:"Eight of Cups",
  desc:"finished journeys", 
  src:"https://live.staticflickr.com/65535/51705111368_c3b17ab55d_m.jpg"},
  {card:"Nine of Cups",
  desc:"wish fulfillment", 
  src:"https://live.staticflickr.com/65535/51705504289_9afea3af2c_m.jpg"},
  {card:"Ten of Cups",
  desc:"community", 
  src:"https://live.staticflickr.com/65535/51705504514_d5c1da7294_m.jpg"},
  {card:"Page of Cups",
  desc:"messages", 
  src:"https://live.staticflickr.com/65535/51704829436_11f1ac4805_m.jpg"},
  {card:"Knight of Cups",
  desc:"carefulness", 
  src:"https://live.staticflickr.com/65535/51705111463_f3469aaff3_m.jpg"},
  {card:"Queen of Cups",
  desc:"emotionality", 
  src:"https://live.staticflickr.com/65535/51705718615_ae207bea48_m.jpg"},
  {card:"King of Cups",
  desc:"benevolence", 
  src:"https://live.staticflickr.com/65535/51705504214_a897149d38_m.jpg"}
];

// The button function

function buttonClick() {
  
// Create a random number generator

var cardsNumber = cards.length;
var randomNumber = Math.random();
var chooseRange = (randomNumber * cardsNumber) + 0;
var numberGen = Math.floor(chooseRange);

// Change HTML
  
  document.getElementById('card').innerHTML = "Your card is " + cards[numberGen].card + "." + "<br> This card is about " + cards[numberGen].desc;
  document.getElementById('face').src = cards[numberGen].src;
  document.getElementById('button').visibility = 'hidden';   
  document.getElementById('button').innerHTML = "Get another card?";

}
        </script>   
<style>
footer {
	position: fixed;
	width: 100%;
	left: 0;
	bottom: 0;
	background-color: #49c6c1;
	color: white;
	text-align: center;
}
</style>

<style>
footer {
	position: static;
	width: 100%;
	left: 0;
	bottom: 0;
	background-color: #dd5e97;
	color: #fadcd1;
	text-align: center;
    font-size: 12px
}
</style>

<footer>
        <p style="font-family: Courier New">
        
<strong>Ko-fi.com/butterflymilkweed</strong>
	<strong>&copy;2021</strong></p>
    
</footer>
