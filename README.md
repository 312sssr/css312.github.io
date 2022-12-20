@font-face {
    font-family: gamefont;
    src: url(https://fonts.gstatic.com/s/daysone/v10/mem9YaCnxnKRiYZOCIYScrg.woff2) format('woff2');
}

#aHolder, #aHider, .endAHolder, #newsHolder, .verticalSeparator, .imageButton, #tlInfHold, #editorBtnM, #gameNameHolder, #seasonLabel {
    display: none !important;
}

* {
	color: #ff9ed0;
}

[style*="color:#eb5656"] {
	color: #ff9ed0 !important;
}

[style*="color:rgba(0,0,0,0.3)"] {
	color: white !important;
}

[style*="color:#9eeb56"] {
	color: white !important;
}

[style*="font-size:20px;color:#fff;display:inline-block;"] {
	color: #ff9ed0 !important;
}

[style*="margin-top:10px;font-size:20px;color:rgba(255,255,255,1)"] {
	display: none !important;
}

a {
    cursor: pointer;
    text-shadow: none;
    color: #ff9ed0;
    text-decoration: none;
    pointer-events: all;
}

#menuItemContainer {
    width: 8%;
    transform: skewX(-2deg);
    position: absolute;
    left: -2%;
}

.xpBarB {
    background: #ff9ed0;
}

.settingsBtn {
    color: #ff9ed0;
    text-align: center;
    display: inline-block;
    width: 75px;
    cursor: pointer;
    background-color: transparent;
    font-size: 17px;
    padding: 4px 8px;
    margin-left: 8px;
    float: right;
    border-radius: 4px;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
}

.menuItem:hover {
    border-left: 0px;
    margin-right: -10%;
    background: linear-gradient(90deg, #ff9ed0, #ff9ed0, #ff9ed0, #ff9ed0, #ff9ed0, #ff9ed0);
}

.menuItem {
    border-right: 5px solid #ff9ed0;
    border-bottom: solid 2px black;
    background: linear-gradient(90deg, rgb(0 0 0), rgb(0 0 0), rgb(0 0 0), rgb(0 0 0), rgb(0 0 0), rgb(0 0 0), rgb(0 0 0), rgb(0 0 0), rgb(0 0 0), #ff9ed0);
}

#windowHolder {
    content: " ";
    position: fixed;
    display: block !important;
    width: 100%;
    height: 100%;
    transform: translateY(100%);
    z-index: 0;
    transition: cubic-bezier(0.36, 0.27, 0, 0.89) .35s;
}

#windowHolder[style*="display: block;"], #windowHolder[style*="display:block;"] {
    position: absolute;
    width: 100%;
    height: 100%;
    transform: translateY(0);
    transition: cubic-bezier(0.36, 0.27, 0, 0.89) .35s;
    background: #0008;
}

.menuTabsNew {
    background: transparent;
}

.setHed {
    background-color: rgba(0,0,0,.3);
}

.tabANew {
    color: #ff9ed0 !important;
    text-shadow: 0 0 15px #ff9ed0;
}

.menuTabNew:hover {
    text-shadow: 0 0 10px #ff9ed0;
}

.tabANew {
    border-bottom: 5px solid #ff9ed0;
}

.tabANew:hover, .menuTabNew:hover {
    border-bottom: 5px solid #ff9ed0;
}

#menuWindow.dark {
    color: black !important;
    box-shadow: none;
    background-color: #00000087;
    backdrop-filter: blur(3px);

}

span {
    color: #ff9ed0;
}

.settName, .settNameSmall, .floatR {
    color: #ff9ed0;
    margin-bottom: 10px;
    font-size: 20px;
}

.settingsHeader {
    background-color: rgb(0 0 0 / 0%);
    backdrop-filter: blur(3px);
}

#uiBase.onMenu #chatHolder {
    position: absolute;
    left: 11%;
    bottom: 10%;
    width: 15%;
}

#chatSwitch {
    display: none;
}

#chatList::-webkit-scrollbar {
    display: none;
}

.chatMsg[style="color:#fc03ec"]{
    color: #ff9ed0 !important
}

.settingTab {
    color: black;
}

.contCanSelect {
    margin-bottom: 1%;
}

#subLogoButtons {
    bottom: 3%;
}

#subLogoButtons>.button {
    height: fit-content;
    box-shadow: none !important;
    background: transparent !important;
    border: solid white 3px;
}

.menuItem .menuItemIcon {
    display: none;
}

div {
    color: #ff9ed0 !important;
}

.menBtnIcn {
    display: none !important;
}

.menuItem .menuItemTitle {
    margin-top: 1%;
    margin-left: 90%;
    align-items: end;
    font-size: 34px !important;
    transform: skewX(-10deg);
    text-shadow: 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black;
}

#uiBase.onMenu #spectButton {
    height: max-content;
    position: absolute;
    top: 4%;
    left: 47%;
    font-size: 30px !important;
    transform: scale(2);
    text-align: center;
    align-content: center;
}

.sliderM {
    vertical-align: middle;
    margin-bottom: -5px;
    -webkit-appearance: none;
    appearance: none;
    width: 100%;
    height: 15px;
    background-color: #ff9ed0;
    outline: none;
    border-radius: 4px;
}

#settSearch {
    width: 100%;
    text-align: left;
    font-size: 16px;
    box-sizing: border-box;
    border: none;
    background-color: transparent;
    border-radius: 4px;
    padding: 6px 10px 5px;
}

.joinBtn {
    color: rgba(255,255,255,.7);
    text-align: center;
    display: inline-block;
    width: 100%;
    cursor: pointer;
    background-color: transparent;
    font-size: 22px;
    padding-top: 8px;
    padding-bottom: 8px;
    border-radius: 4px;
}

.headerBarRight {
    background: transparent;
    top: 1%;
    right: 1%;
}

#menuServerInfoContainer, #menuPingText {
    font-size: 25px;
    top: 7%;
}

#menuPingDisplay .material-icons {
    display: none;
}

.menuSocialB {
    display: none;
}

#menuKRCount {
    font-size: 15px;
    width: -webkit-fill-available;
}

.headerBarLeft {
    width: fit-content;
    padding-right: 3%;
}

.serverHeader, #selectorContainer, #itemSearchH {
    background: transparent;
}

.selectorItem {
    border-radius: 0px;
    background: transparent !important;
    filter: drop-shadow(2px 2px 2px #ff9ed0) !important;
}

.selectedItem {
    border-radius: 0px;
    filter: drop-shadow(2px 2px 2px #ff9ed0) !important;
}

.selectorItem:hover {
    border-left: 10px solid #ff9ed0;
}

.custContainer:hover {
    background: rgb(0 0 0 / 50%)
}

#teamSelector {
    position: fixed;
    bottom: 10%;
}

#mailIcon {
    margin-right: -50%;
}

#customizeButton {
    box-shadow: none !important;
    background: transparent !important;
    border: solid white 3px;
    height: 400px;
    width: 400px;
    font-size: 0px !important;
    position: absolute;
    left: 110px;
    margin-top: -350px;
}

.material-icons {
    color: #ff9ed0 !important;
}

#leaderDisplay {
    position: relative;
    border-radius: 0px;
    background: rgba (0, 0, 0, .6);
    box-shadow: 3px 3px 2px #ff9ed0, 4px 4px 2px #ff9ed0, 5px 5px 2px #ff9ed0, 6px 6px 2px #ff9ed0;
    left: -10%;
}

#leaderContainer {
    border-top: 4px solid #ff9ed0;
}

#leaderDisplay:before {
    content: "Leaderboard";
    color: black;
    text-shadow: 1px 1px #ff9ed0, -1px -1px #ff9ed0, -1px 1px #ff9ed0, 1px -1px #ff9ed0;
    width: 400px;
    padding: 10px;
}

.leaderCounter {
    color: #ff9ed0 !important;
    text-shadow: 1px 1px black, -1px -1px black, -1px 1px black, 1px -1px black;
}

.leaderNameM, .leaderNameF {
    color: #ff9ed0 !important;
    text-shadow: 1px 1px black, -1px -1px black, -1px 1px black, 1px -1px black;
}

.leaderName {
    color: black !important;
    text-shadow: 1px 1px #ff9ed0, -1px -1px #ff9ed0, -1px 1px #ff9ed0, 1px -1px #ff9ed0;
}

#uiBase.onMenu #voiceDisplay {
    left: 26%;
    bottom: 10%;
}

.topRightCounters {
    transform: scale(1);
}

.countIcon {
    border-radius: 6px;
    background-color: rgba(0,0,0,.3);
    font-size: 40px;
}

#killsIcon, #deathsIcon, #streakIcon, #kdIcon {
    width: 50px;
    height: 50px;
}

#kdVal, #deathsVal, #killsVal, #livesDisp, #streakVal, #myScoreVal {
    color: #ff9ed0;
}

#menuClassNameTag {
    display: none;
}

#timerDisplay {
    background: transparent;
    position: fixed;
    top: 85%;
    left: 52%;
    align-content: left;
    text-align: left;
    margin: 0px;
}

#timerIcon {
    display: none;
}

#timerVal {
    color: black;
    text-shadow: 2px 2px #ff9ed0, -2px -2px #ff9ed0, -2px 2px #ff9ed0, 2px -2px #ff9ed0;
    font-size: 40px;
}

#pingDisplay, #fpsDisplay, #ingressDisplay, #egressDisplay, span#ingameFPS, #pingText, #ingressPacketCount, #ingressDataSize, #egressPacketCount, #egressDataSize, #pingDisplay, .material-icons, #ingressDisplay .material-icons, #egressDisplay .material-icons {
    color: #ff9ed0 !important;
    text-shadow: 1px 1px 1px black, -1px -1px 1px black, -1px 1px 1px black, 1px -1px 1px black;
    font-size: 32px;
}

#curGameInfo {
    font-size: 16px;
    text-shadow: 1px 1px 1px black, -1px -1px 1px black, -1px 1px 1px black, 1px -1px 1px black;
}

#reloadMsg{
    font-size: 0;
    border: transparent;
    background: transparent;
    top: 53%;
}

#reloadMsg::before{
    content: 'reload bruh';
    font-size: 20px;
    left: 50%;
    top: 53%;
    color: #ff9ed0 !important;
    text-shadow: 1px 1px black, -1px -1px black, -1px 1px black, 1px -1px black;   
}
    
#ammoDisplay {
    background-color: transparent;
    position: fixed;
    top: 52.1%;
    padding-top: 0px;
    height: 6px;
    padding: 0px;
    padding-left: 0px;
    padding-right: 0px;
    width: 60px;
    left: 48.6%;
    border-radius: 2px;
    background-image: url(https://cdn.discordapp.com/attachments/624768972428017689/852464070083084298/pink_reload.png);
}

#ammoMax, #ammoIcon {
    display: none;
}

#ammoVal {
    position: fixed;
    top: 3000%;
    left: 400%;
    font-size: 64px;
    text-shadow: 1px 1px 3px black, -1px -1px 3px black, -1px 1px 3px black, 1px -1px 3px black;
}

#hudClassIcon {
    display: none;
}

#healthBar {
    align-content: center;
    position: fixed;
    left: 43.5%;
    bottom: 5%;
    border: solid 8px transparent;
    align-content: right;
    transform: scaleX(2) skew(-10deg);
    height: 30px;
}

.hpBSeg {
    border-radius: 0px;
    box-shadow: none;
}

.healthBarSeg {
    display: none;
}

#healthValueHolder {
    background: transparent;
    position: fixed;
    top: 67.5%;
    left: 35%;
    text-shadow: 1px 1px 3px black, -1px -1px 3px black, -1px 1px 3px black, 1px -1px 3px black;
}

#healthValue {
    color: #ff9ed0 !important;
    font-size: 64px;
}

#maxHP, #challIcon {
    display: none;
}

#killCardHolder {
    text-shadow: 1px 1px 3px black, -1px -1px 3px black, -1px 1px 3px black, 1px -1px 3px black;
    color: black !important;
}

.standout {
    color: transparent !important;
    font-size: 0px;
}

.standout:before {
    content: " ";
    color: transparent;
    font-size: 15px;
}

.grey {
    color: white;
}

.clsXPBarC {
    width: 100% !important;
    background-color: #ff9ed0;
}

.classCard {
    background-color: #1b1c1c;
    border-radius: 0px;
    box-shadow: 6px 6px 2px #ff9ed0;
    margin-right: 2px;
}

.weapKey {
    display: none;
}

.weapIcon {
    transform: translate(-50%,-50%);
    position:fixed;
    left: 55.5%;
    bottom: -1%;
    opacity: 0 !important;
    transition-duration: .25s;
    filter: brightness(0) drop-shadow(1px 1px #ff9ed0) drop-shadow(-1px -1px #ff9ed0) drop-shadow(-1px 1px #ff9ed0) drop-shadow(1px -1px #ff9ed0);
}

.weapIcon[style*="opacity: 1;"] {
    opacity: 1 !important;
}

.weapIcon[style*="opacity: 0.7;"] {
    transform:translate(-50%,-50%) translateY(200px);
}

.setHedBind, .setHed {
    margin-bottom: 10px;
    color: #ff9ed0 !important;
    border: unset;
    border-bottom: 4px solid #ff9ed0;
    margin-top: 20px;
}

.custContainer {
    background: #ffffff4d;
    margin-bottom: 0px;
}

#termsInfo {
    padding-bottom: 0px;
    padding-top: 0px;
    border: 0px;
    height: fit-content;
}

#mapInfo {
    margin-bottom: 0px;
    font-size: 32px;
}

.verticalSeparatorInline {
    height: 0px;
    margin: 0px;
}

.mapActionOvrl {
    height: 81%;
    background-color: #ff9ed04f;
}

.weaponChatIcon, .headShotChatIcon, .meleeChatIcon, .thrownChatIcon {
    filter: brightness(0) drop-shadow(1px 1px #ff9ed0) drop-shadow(-1px -1px #ff9ed0) drop-shadow(-1px 1px #ff9ed0) drop-shadow(1px -1px #ff9ed0);
    opacity: 1 !important;
    drop-shadow: 
}

#mapInfoHolder {
    height: fit-content;
    width: 30%;
}

.terms {
    font-size: 16px;
}

.verticalSeparatorInline {
    display: none;
}

.standout {
    font-size: 0px !important;
}

#instructionsUpdate {
    background: black;
    color: black !important;
    box-shadow: 5px 5px 1px #ff9ed0, 6px 6px 1px #ff9ed0, 7px 7px 1px #ff9ed0;
}

#instructionsUpdateBG {
    background: transparent;
}

#instructionHolder {
    background-color: rgb(0 0 0 / 0.5);
}

#policeButton {
    margin-left: 12px;
    top: 90px;
    color: #fff;
    display: inline-block;
    border-radius: 6px;
    transform: scale(1.5);
}

.slider, input:checked+.slider, .slider:before, input:checked+.slider:before {
    border-radius: 12px;
}

input:checked+.slider {
    background: #ff9ed0;
}

.slider, input[type=number] {
    background: black;
}

input[type=color] {
    border: 4px solid #ff9ed0;
}

div#menuBtnProfile, div#menuBtnShop {
    font-size: 0 !important;
}

div#menuBtnProfile:after {
    font-size: 33px !important;
    content : "Profile"
}

div#menuBtnShop:after {
    font-size: 33px !important;
    content: "Shop"
}

::-webkit-scrollbar-track {
	-webkit-box-shadow: none;
	box-shadow: none;
	background-color: transparent !important;
}

::-webkit-scrollbar {
	width: 12px !important;
}

::-webkit-scrollbar-thumb {
	background-color: #ff9ed0;
	-webkit-box-shadow: none;
	box-shadow: none;
}

#modVote {
    color: #ff9ed0;
    font-size: 32px;
    margin-bottom: 10px;
    text-align: right;
}

.voteHint {
    color: #fff;
    font-size: 15px;
    margin-top: -6px;
    border: 0px;
    padding: 5px;
    padding-left: 10px;
    padding-right: 10px;
    border-radius: 4px;
    vertical-align: middle;
    display: inline-block;
    cursor: pointer;
    background-color: transparent;
    -webkit-transition: all .08s;
    transition: all .08s;
}

.vHR {
    border: transparent !important;
    font-size: 28px;
    background-color: transparent;
}

.button, .button:hover { 
    border: hidden !important;
}

.quickJoin {
    float: right;
    border-radius: 5px;
    border: transparent;
    font-size: 20px;
    padding: 6px;
    cursor: pointer;
    pointer-events: all;
    z-index: 99999;
    display: inline-block;
    margin-right: 15px;
    color: #fff;
    margin-top: -3px;
    vertical-align: top;
    -webkit-transition: all .08s;
    transition: all .08s;
}

#faceItIconM, #rankedSoonTm {
    display: none
}

.sliderSml {
    background-color: black;
}

input:checked+.sliderSml {
    background-color: #ff9ed0;
}

#chatInput {
	background-color: transparent;
	font-size: 16px;
}

.chatItem {
    word-wrap: break-word;
    display: inline-block;
    margin-bottom: 10px;
    margin-top: 10px;
    margin-left: 12px;
    font-size: 16px;
    max-width: fit-content;
}

#uiBase.onMenu #spectateUI {
    display: block!important;
    position: fixed;
    bottom: 60%;
    top: unset;
    left: 50%;
    right: unset;
    transform: translate(-50%, 50%);
    z-index: 1;
    width: 10px;
    height: 10px;
}

#uiBase.onMenu #spectateHUD {
    display: flex;
    justify-content: center;
    transform: unset;
    left: unset;
    top: -250px;
}

#uiBase.onMenu #specTeam0, #uiBase.onMenu #spec0, #uiBase.onMenu #spec1, #uiBase.onMenu #specNames, #uiBase.onMenu #specStats, #uiBase.onMenu #specContr, #uiBase.onMenu #specKPDContr, #uiBase.onMenu #specSus, #uiBase.onMenu #specTeam1, #uiBase.onMenu #specGMessage, #uiBase.onMenu #specGameInfo {
    display: none!important
}

#uiBase.onMenu #specTimer {
    display: block!important;
    font-size: 80px;
    background-color: transparent;
    color: #ff9ed0;
    text-shadow: 2px 2px 10px #ff9ed0;
}

* {
    cursor: url(https://cdn.discordapp.com/attachments/624768972428017689/879615478937575474/astolfo_cursor.png), auto!important;
}

#initLoader {
  background-image: url(https://cdn.donmai.us/original/49/e3/__astolfo_and_astolfo_fate_and_2_more_drawn_by_samoore__49e375be03af6b92d05529657528bb73.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}

#loadEditrBtn {
    display: none;
}

#loadTipsHolder {
    bottom: unset;
    top: 128px;
    width: unset;
    font-size: 0;
}

#loadTipsHolder::before {
    content: "Astolfo ClientTM";
    font-size: 64px;
    color: #131313;
    background-color: #ff9ed0;
    padding: 0 32px;
    padding-top: 12px;
}

#loadTipsHolder::after {
    content: "";
    font-size: 32px;
    color: #131313;
    position: absolute;
    right: 36px;
    bottom: 4px;
}

#loadTipsHolder span {
    display: none;
}

#loadGamNm {
    font-size: 32px;
    color: #000;
    text-shadow: 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black;
}

.lC-cube {
    display: none;
}

#loadInfoLHolder {
    font-size: 0;
    color: #fff;
}

#loadInfoLHolder::before {
    content: "";
    font-size: 32px;
}

#lC-cont::before {
    content: " ";
    display: block;
    width: 120px;
    height: 120px;
    background-color: transparent;
    background-image: url(https://emoji.gg/assets/emoji/1648_AstolfoPlushie.gif);
    background-size: 75%;
    background-repeat: no-repeat;
    background-position: center;
}

#loadInfoRHolder {
    font-size: 0;
    color: #fff;
}

#loadInfoRHolder::before {
    content: "";
    font-size: 32px;
}

#bottomLeftHolder::before {
    content: " ";
    background: url(https://cdn.discordapp.com/attachments/624768972428017689/937307558845231114/1643541910903.png);
    background-size: 250px;
    background-position-x: center;
    background-position-y: top;
    width: 250px;
    height: 330px;
    position: fixed;
    bottom: 0px;
    right: calc(50% - 12px);
}

#endTimer {
    color: #fff;
    font-style: normal;
    text-shadow: black;
}

#matchVoteHolder {
    background-color: transparent;
    top: 210px;
}

.matchVote {
    box-shadow: 6px 6px #ff9ed0;
    border-radius: 0;
    border: 6px solid black;
}

.endCard {
    background-color: rgba(0,0,0,.6);
    border-radius: 0;
    box-shadow: 8px 8px #ff9ed0;
}

#tabHolder {
    border-radius: 0;
    background-color: transparent;
    position: relative;
    margin-top: 4px;
    right: -12px;
    width: calc(100% + 20px);
}

.tabHeader {
    border-width: 0 !important;
    color: #fff;
    font-size: 20px;
}

#endTable {
    background-color: transparent;
}

th, td {
    color: #ff9ed0;
}

td[style*="#fff"] {
    color: #ff9ed0 !important;
}

.endTableN {
    color: #ff9ed0;
}

.endTableN[style*="#eb5656"] {
    color: #ff9ed0 !important;
}

.endTableN[style*="#fff"] {
    color: #fff !important;
}

.endTableN[style*="#fff"]::before {
    content: "》";
    -webkit-text-stroke: 2px;
    margin-right: 4px;
    margin-left: 0px;
    color: #ff9ed0;
}

.endTableN[style*="rgba(255,255,255,0.6)"] {
    color: #ff9ed0 !important;
}

.endTableN span[style*="#fff"] {
    color: #ff9ed0 !important;
}

.reportBut {
    color: #ff9ed0;
    text-shadow: none;
}

.shareBut {
    color: #fff !important;
    text-shadow: none;
}

.endSection {
    background-color: transparent;
}

.endTitle, .fundsVal {
    color: #ff9ed0;
}

.endTitle {
    font-size: 20px;
}

.gfSection {
    background-color: transparent;
}

.modeIcon {
    filter: drop-shadow(2px 2px #000) drop-shadow(-2px -2px #000) drop-shadow(-2px 2px #000) drop-shadow(2px -2px #000) drop-shadow(2px 2px #000);
}

.modeStatus {
    color: #ff9ed0;
    font-size: 24px;
}

.crStat {
    border-radius: 0;
    background-color: #000;
    border-width: 0;
}

.crLabel {
    font-size: 16px;
    color: #ff9ed0;
}

#kdLayout {
    background-color: #000;
    border-width: 0;
    border-radius: 0;
}

.endTitle, .fundsVal {
    color: #fff;
}

.xpEndBar {
    border-radius: 0;
    background-color: #000;
}

.clanwarsSection {
    background-color: transparent;
}

#cwRegionOcean {
    border-radius: 0;
}

#cwRegionMap {
    border-radius: 0;
    box-shadow: none;
    filter: none;
    box-shadow: inset 0 0 0 8px;
}

.cwSumStat {
    background-color: #000;
    border-radius: 0;
}

#cwRegionText {
    color: #fff;
    text-transform: uppercase;
}

.cwSumStat {
    background-color: #000;
    border-radius: 0;
}

#cwRegionText {
    display: none;
}

#mLevelCont {
    display: inline-block;
    background-color: transparent;
    border-bottom-right-radius: 10px;
    padding-left: 15px;
    padding-right: 4px;
    height: 70px;
    margin-left: 20px;
}

#instructions {
    font-size: 0px;
    animation: none
}

.hostToggle {
    border-radius: 0;
    background-color: #000;
}

#rawMapData {
    border-radius: 0;
    font-size: 24px;
}

.hostMap {
    border: none;
    height: 94px;
    width: 220px;
}

.hostMapBy, .hostMapYear, .hostMapVersion {
    display: none;
}

.hostMapName {
    top: 50%;
    left: 50%;
    font-size: 24px;
    width: 100%;
    text-align: center;
    transform: translate(-50%, -50%);
}

.hostMapImg {
    filter: grayscale(100%) brightness(.75);
    border-radius: 0;
    width: 232px;
}

.hostMap .blackShad {
    text-shadow: none;
}

.optCheck {
    transition-duration: 0.25s;
    background-color: black;
}

input:checked+.optCheck {
    background-color: #ff9ed0;
}

.hostOpt {
    border-radius: 4;
    border: 0;
    width: 212px;
}

.optName {
    text-shadow: none;
}

#hostMenuBtn {
    display: none;
}

.followBack {
    padding-left: 10px;
    border: 0px #fff !important;
}

.followBack::hover {
    padding-left: 10px;
    border: 0px #fff !important;
}

.tScoreC {
    background-color: #ff9ed0;
    border-radius: 50%;
}

.tScoreT {
    font-size: 32px;
    color: black;
    text-shadow: 2px 2px #ff9ed0, -2px -2px #ff9ed0, -2px 2px #ff9ed0, 2px -2px #ff9ed0;
}

.teamTotalN0 {
    color: #ff9ed0;
    font-size: 19px;
    padding-left: 10px;
}

.teamTotalN1 {
    color: white;
    font-size: 19px;
    padding-left: 10px;
}

.inputGrey2 {
    border: none;
    background: rgba(255,255,255,.3);
    padding: 6px;
    padding-bottom: 6px;
    float: right;
    margin-left: 10px;
    font-size: 15px;
    border-radius: 4px;
}

#menuMiniProfilePic {
    content: url(https://cdn.discordapp.com/attachments/624768972428017689/940793103613329418/images.png);
    transform: scale(1.3);
}

#profilePicM {
    content: url(https://cdn.discordapp.com/attachments/624768972428017689/940793103613329418/images.png);
    filter: none;
    border: none;
}

.searchBtn {
    background-color: transparent;
}

#gameMessage {
    margin-top: 20px;
    font-size: 32px;
    filter: drop-shadow(1px 1px #000) drop-shadow(-1px -1px #000) drop-shadow(-1px 1px #000) drop-shadow(1px -1px #000);
}

.progressBarInner {
    height: 100%;
    background-image: linear-gradient(to right,#ff9ed0,90%,white);
    transition: width 1s ease-in-out;
    border-radius: 4px;
}

.chalXPBarC {
    background-image: linear-gradient(to right,#ff9ed0, 90%,white);
    height: 100%;
    font-size: 16px;
    border-radius: 4px;
}
