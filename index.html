
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<title>TIC TAC TOE ULTIMATE</title>
<script src="https://unpkg.com/peerjs@1.5.4/dist/peerjs.min.js"></script>
<style>
*{box-sizing:border-box}
:root{--bg:#090d19;--panel:#121a2c;--line:#25334d;--text:#f3f6ff;--muted:#8492ac;--blue:#6c8cff;--pink:#ff639e;--green:#40e0b0}
body{
 margin:0;min-height:100vh;background:
 radial-gradient(ellipse at 15% 0%,#1b2850 0,transparent 45%),
 radial-gradient(ellipse at 90% 90%,#291a49 0,transparent 40%),var(--bg);
 color:var(--text);font-family:system-ui,-apple-system,sans-serif;
 display:flex;justify-content:center;padding:20px 12px 40px;
}
.app{width:100%;max-width:520px}
header{text-align:center;margin:12px 0 25px}
.logo{font-size:12px;letter-spacing:5px;color:var(--blue);font-weight:900}
h1{font-size:34px;letter-spacing:-1.5px;margin:7px 0}
h1 span{color:var(--blue)}
.subtitle{color:var(--muted);font-size:13px}
.panel{
 background:linear-gradient(145deg,#17223a,#10182a);
 border:1px solid var(--line);border-radius:20px;padding:17px;margin-bottom:14px;
 box-shadow:0 12px 35px #0004;
}
.section-title{font-size:12px;color:var(--muted);font-weight:800;letter-spacing:1.5px;margin-bottom:12px}
.modes,.sizes,.difficulties{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
button{
 border:1px solid var(--line);background:#1b2740;color:var(--text);
 border-radius:12px;padding:12px 7px;font-size:13px;font-weight:750;
 cursor:pointer;transition:.2s; -webkit-tap-highlight-color:transparent;
}
button:active{transform:scale(.96)}
button.active{background:linear-gradient(135deg,#536fff,#8068f7);border-color:transparent;box-shadow:0 5px 20px #536fff55}
button.primary{background:linear-gradient(135deg,#557aff,#9266ff);border:0}
button.secondary{background:#202e49}
button:disabled{opacity:.4}
.game-info{display:flex;justify-content:space-between;align-items:center;margin-bottom:14px}
.player{flex:1;text-align:center;padding:12px 5px;border:1px solid var(--line);border-radius:14px;background:#111b30}
.player.current{border-color:var(--blue);background:#26365b;box-shadow:0 0 20px #557aff33}
.symbol{font-size:25px;font-weight:900}
.x{color:#6e9aff;text-shadow:0 0 18px #6e9aff88}
.o{color:#ff70aa;text-shadow:0 0 18px #ff70aa88}
.player-name{font-size:11px;color:var(--muted);margin-top:3px}
.vs{padding:0 9px;color:#67758f;font-size:11px;font-weight:900}
.status{text-align:center;font-size:14px;font-weight:750;margin:14px 0;color:#dce5ff;min-height:21px}
.board-wrap{padding:12px;background:#0b1324;border:1px solid #283958;border-radius:19px}
.board{display:grid;gap:7px;aspect-ratio:1}
.cell{
 min-width:0;min-height:0;border-radius:12px;border:1px solid #283955;
 background:linear-gradient(145deg,#17243a,#101a2d);
 display:flex;align-items:center;justify-content:center;
 font-size:clamp(25px,9vw,48px);font-weight:950;
 transition:background .2s,border .2s;
}
.board.four .cell{font-size:clamp(22px,7vw,38px)}
.board.five .cell{font-size:clamp(19px,6vw,32px);border-radius:8px}
.cell:not(:disabled){cursor:pointer}
.cell:not(:disabled):active{background:#263b60}
.cell.win{background:#214b4a;border-color:var(--green);animation:winPulse .8s infinite alternate}
.cell.pop{animation:pop .25s ease-out}
@keyframes pop{0%{transform:scale(.5);opacity:.2}100%{transform:scale(1);opacity:1}}
@keyframes winPulse{to{box-shadow:0 0 17px #40e0b077}}
.actions{display:grid;grid-template-columns:1fr 1fr;gap:9px;margin-top:14px}
.actions button{padding:13px}
.score{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:14px}
.score div{background:#101a2d;border:1px solid var(--line);padding:10px;border-radius:12px;text-align:center}
.score strong{display:block;font-size:21px}
.score small{font-size:10px;color:var(--muted)}
.online{display:none}
.online.show{display:block}
.online-row{display:flex;gap:8px;margin-top:9px}
.online-row input{
 min-width:0;flex:1;background:#0b1425;color:white;border:1px solid var(--line);
 border-radius:11px;padding:12px;font-size:15px;outline:none;text-transform:uppercase;
}
.online-info{font-size:12px;color:var(--muted);margin-top:10px;line-height:1.5}
.room-code{font-size:25px;letter-spacing:6px;color:#8da7ff;font-weight:900;text-align:center;padding:10px}
.hidden{display:none!important}
.notice{text-align:center;color:var(--muted);font-size:11px;margin-top:20px}
#toast{position:fixed;bottom:25px;left:50%;transform:translateX(-50%);background:#263957;border:1px solid #536fff;color:white;padding:12px 18px;border-radius:12px;display:none;z-index:10;max-width:90%;text-align:center}
@media(max-width:370px){h1{font-size:28px}.panel{padding:13px}.cell{gap:4px}}
</style>
</head>
<body>
<div class="app">
<header>
 <div class="logo">MB GAMES PRESENTS</div>
 <h1>TIC TAC <span>TOE</span></h1>
 <div class="subtitle">ULTIMATE EDITION · PLAY YOUR WAY</div>
</header>

<div class="panel">
 <div class="section-title">РЕЖИМ ИГРЫ</div>
 <div class="modes">
  <button class="active" data-mode="bot" onclick="setMode('bot',this)">🤖 С ботом</button>
  <button data-mode="local" onclick="setMode('local',this)">👥 Вдвоём</button>
  <button data-mode="online" onclick="setMode('online',this)">🌐 Онлайн</button>
 </div>
</div>

<div class="panel">
 <div class="section-title">РАЗМЕР ПОЛЯ</div>
 <div class="sizes">
  <button class="active" onclick="setSize(3,this)">3 × 3</button>
  <button onclick="setSize(4,this)">4 × 4</button>
  <button onclick="setSize(5,this)">5 × 5</button>
 </div>
 <div class="section-title" style="margin-top:17px">СЛОЖНОСТЬ БОТА</div>
 <div class="difficulties">
  <button class="active" onclick="setDifficulty('easy',this)">Лёгкий</button>
  <button onclick="setDifficulty('medium',this)">Средний</button>
  <button onclick="setDifficulty('hard',this)">Сложный</button>
 </div>
</div>

<div class="panel online" id="onlinePanel">
 <div class="section-title">ОНЛАЙН МУЛЬТИПЛЕЕР</div>
 <div class="online-row">
  <button class="primary" style="flex:1" onclick="createRoom()">Создать комнату</button>
 </div>
 <div class="online-info">Создай комнату и отправь другу код. Друг должен ввести код и нажать «Подключиться».</div>
 <div id="roomArea" class="hidden">
  <div class="room-code" id="roomCode"></div>
  <button class="secondary" style="width:100%" onclick="copyRoom()">📋 Скопировать код</button>
 </div>
 <div class="online-row">
  <input id="joinCode" maxlength="6" placeholder="КОД КОМНАТЫ">
  <button class="primary" onclick="joinRoom()">Войти</button>
 </div>
 <div class="online-info" id="netStatus">Ожидание подключения.</div>
</div>

<div class="panel">
 <div class="game-info">
  <div class="player current" id="playerX">
   <div class="symbol x">✕</div><div class="player-name" id="nameX">Игрок 1</div>
  </div>
  <div class="vs">VS</div>
  <div class="player" id="playerO">
   <div class="symbol o">◯</div><div class="player-name" id="nameO">Бот</div>
  </div>
 </div>

 <div class="status" id="status">Ход крестиков</div>
 <div class="board-wrap">
  <div class="board" id="board"></div>
 </div>
 <div class="actions">
  <button class="primary" onclick="newGame()">↻ Новая игра</button>
  <button class="secondary" onclick="resetScore()">Сбросить счёт</button>
 </div>
 <div class="score">
  <div><strong class="x" id="scoreX">0</strong><small>КРЕСТИКИ</small></div>
  <div><strong id="scoreDraw">0</strong><small>НИЧЬИ</small></div>
  <div><strong class="o" id="scoreO">0</strong><small>НОЛИКИ</small></div>
 </div>
</div>
<div class="notice">TIC TAC TOE ULTIMATE · MADE FOR FUN</div>
</div>
<div id="toast"></div>

<script>
let size=3, winLength=3, mode='bot', difficulty='easy';
let board=[],turn='X',finished=false,score={X:0,O:0,D:0};
let peer=null,connection=null,room='',mySide='X',onlineReady=false;
let winningCells=[];

const $=id=>document.getElementById(id);

function toast(message){
 const t=$('toast');t.textContent=message;t.style.display='block';
 clearTimeout(toast.timer);toast.timer=setTimeout(()=>t.style.display='none',2400);
}
function setMode(m,btn){
 if(mode==='online'&&m!=='online') disconnect();
 mode=m;
 document.querySelectorAll('[data-mode]').forEach(b=>b.classList.toggle('active',b.dataset.mode===m));
 $('onlinePanel').classList.toggle('show',m==='online');
 $('nameX').textContent=m==='bot'?'Ты':m==='online'?'Ты (X)':'Игрок 1';
 $('nameO').textContent=m==='bot'?'Бот':m==='online'?'Друг (O)':'Игрок 2';
 newGame();
}
function setSize(n,btn){
 size=n;winLength=n===5?4:n;
 document.querySelectorAll('.sizes button').forEach(b=>b.classList.remove('active'));
 btn.classList.add('active');newGame();
}
function setDifficulty(d,btn){
 difficulty=d;
 document.querySelectorAll('.difficulties button').forEach(b=>b.classList.remove('active'));
 btn.classList.add('active');
}
function newGame(){
 board=Array(size*size).fill('');
 turn='X';finished=false;winningCells=[];
 render();updateStatus();
 if(mode==='online'&&mySide==='O'&&onlineReady) updateStatus('Ожидаем ход игрока X');
}
function render(){
 const el=$('board');
 el.innerHTML='';
 el.style.gridTemplateColumns=`repeat(${size},1fr)`;
 el.className='board '+(size===4?'four':size===5?'five':'');
 board.forEach((v,i)=>{
  const b=document.createElement('button');
  b.className='cell'+(winningCells.includes(i)?' win':'');
  b.textContent=v==='X'?'✕':v==='O'?'◯':'';
  if(v)b.classList.add('pop',v==='X'?'x':'o');
  b.disabled=!!v||finished||(mode==='online'&&(!onlineReady||turn!==mySide));
  b.onclick=()=>play(i);
  el.appendChild(b);
 });
 $('scoreX').textContent=score.X;
 $('scoreO').textContent=score.O;
 $('scoreDraw').textContent=score.D;
 $('playerX').classList.toggle('current',turn==='X'&&!finished);
 $('playerO').classList.toggle('current',turn==='O'&&!finished);
}
function updateStatus(message){
 if(message){$('status').textContent=message;return}
 if(finished)return;
 if(mode==='online'&&!onlineReady){$('status').textContent='Ожидаем второго игрока...';return}
 $('status').textContent=turn==='X'?'Ход крестиков':'Ход ноликов';
}
function getWinner(arr){
 const dirs=[[0,1],[1,0],[1,1],[1,-1]];
 for(let r=0;r<size;r++)for(let c=0;c<size;c++){
  const i=r*size+c,s=arr[i];if(!s)continue;
  for(const [dr,dc] of dirs){
   let cells=[i],ok=true;
   for(let k=1;k<winLength;k++){
    let nr=r+dr*k,nc=c+dc*k;
    if(nr<0||nr>=size||nc<0||nc>=size||arr[nr*size+nc]!==s){ok=false;break}
    cells.push(nr*size+nc);
   }
   if(ok)return {winner:s,cells};
  }
 }
 return null;
}
function play(i,remote=false){
 if(finished||board[i]|| (mode==='online'&&!remote&&(!onlineReady||turn!==mySide)))return;
 board[i]=turn;
 const result=getWinner(board);
 if(result){
  finished=true;winningCells=result.cells;score[result.winner]++;
  render();
  $('status').textContent=result.winner==='X'?'✕ Крестики победили!':'◯ Нолики победили!';
  if(mode==='online'&&!remote)send({type:'move',index:i});
  return;
 }
 if(board.every(Boolean)){
  finished=true;score.D++;render();$('status').textContent='🤝 Ничья!';
  if(mode==='online'&&!remote)send({type:'move',index:i});
  return;
 }
 turn=turn==='X'?'O':'X';
 render();updateStatus();
 if(mode==='online'&&!remote)send({type:'move',index:i});
 if(mode==='bot'&&turn==='O'&&!finished)setTimeout(botMove,350);
}
function botMove(){
 if(finished||mode!=='bot')return;
 let i;
 if(difficulty==='hard'&&size===3)i=minimax(board,'O').index;
 else i=smartMove();
 if(i!==undefined&&i!==null)play(i);
}
function minimax(arr,player){
 const result=getWinner(arr);
 if(result)return {score:result.winner==='O'?10:-10};
 if(arr.every(Boolean))return {score:0};
 let best={score:player==='O'?-Infinity:Infinity,index:null};
 for(let i=0;i<arr.length;i++)if(!arr[i]){
  arr[i]=player;
  const value=minimax(arr,player==='O'?'X':'O').score;
  arr[i]='';
  if(player==='O'?value>best.score:value<best.score)best={score:value,index:i};
 }
 return best;
}
function smartMove(){
 const empty=board.map((v,i)=>v===''?i:-1).filter(i=>i>=0);
 if(!empty.length)return null;
 if(difficulty==='easy'&&Math.random()<.55)return empty[Math.floor(Math.random()*empty.length)];
 // Ищем выигрышный ход и возможность остановить победу игрока.
 for(const symbol of ['O','X']){
  for(const i of empty){
   board[i]=symbol;let wins=!!getWinner(board);board[i]='';
   if(wins)return i;
  }
 }
 if(difficulty==='hard'){
  let best=-Infinity,chosen=empty[0];
  for(const i of empty){
   board[i]='O';
   let value=evaluateBoard();
   board[i]='';
   value+=Math.random()*.2;
   if(value>best){best=value;chosen=i}
  }
  return chosen;
 }
 const center=(size-1)/2;
 empty.sort((a,b)=>{
  let ar=Math.floor(a/size),ac=a%size,br=Math.floor(b/size),bc=b%size;
  return Math.hypot(ar-center,ac-center)-Math.hypot(br-center,bc-center);
 });
 return difficulty==='medium'?empty[0]:empty[Math.floor(Math.random()*empty.length)];
}
function evaluateBoard(){
 let value=0,dirs=[[0,1],[1,0],[1,1],[1,-1]];
 for(let r=0;r<size;r++)for(let c=0;c<size;c++)for(const [dr,dc] of dirs){
  let cells=[];
  for(let k=0;k<winLength;k++){
   let nr=r+dr*k,nc=c+dc*k;
   if(nr<0||nr>=size||nc<0||nc>=size)break;
   cells.push(board[nr*size+nc]);
  }
  if(cells.length!==winLength)continue;
  let o=cells.filter(x=>x==='O').length,x=cells.filter(x=>x==='X').length;
  if(!x)value+=Math.pow(4,o);
  if(!o)value-=Math.pow(4,x)*1.1;
 }
 return value;
}
function resetScore(){score={X:0,O:0,D:0};render();toast('Счёт обнулён')}
function send(data){
 if(connection&&connection.open)connection.send(data);
}
function disconnect(){
 if(connection){connection.close();connection=null}
 if(peer){peer.destroy();peer=null}
 onlineReady=false;room='';
 $('roomArea').classList.add('hidden');
 $('netStatus').textContent='Отключено.';
}
function createRoom(){
 disconnect();
 room=Math.random().toString(36).substring(2,8).toUpperCase();
 mySide='X';newGame();
 $('netStatus').textContent='Создаём комнату...';
 peer=new Peer('mbttt-'+room);
 peer.on('open',()=>{
  $('roomCode').textContent=room;
  $('roomArea').classList.remove('hidden');
  $('netStatus').textContent='Комната создана. Ожидаем друга...';
 });
 peer.on('connection',conn=>{
  if(connection){conn.close();return}
  connection=conn;setupConnection();
 });
 peer.on('error',e=>{$('netStatus').textContent='Ошибка соединения: '+e.type;});
}
function joinRoom(){
 const code=$('joinCode').value.trim().toUpperCase();
 if(code.length!==6){toast('Введите шестизначный код');return}
 disconnect();room=code;mySide='O';newGame();
 $('netStatus').textContent='Подключаемся...';
 peer=new Peer();
 peer.on('open',()=>{
  connection=peer.connect('mbttt-'+room);
  setupConnection();
 });
 peer.on('error',e=>{$('netStatus').textContent='Не удалось подключиться: '+e.type});
}
function setupConnection(){
 if(!connection)return;
 connection.on('open',()=>{
  onlineReady=true;
  $('netStatus').textContent='Соединение установлено! Вы играете за '+mySide;
  if(mySide==='X')send({type:'start',size});
  else send({type:'hello',size});
  render();updateStatus();
 });
 connection.on('data',data=>{
  if(data.type==='hello'&&mySide==='X'){
   if(data.size!==size){send({type:'reject'});toast('У вас разные размеры поля');return}
   onlineReady=true;send({type:'start',size});render();updateStatus();
  }
  if(data.type==='start'){
   if(data.size!==size){toast('Размер поля не совпадает');return}
   onlineReady=true;render();updateStatus('Игра началась! Ваш ход за '+mySide);
  }
  if(data.type==='reject')toast('Размер поля не совпадает');
  if(data.type==='move'){
   if(!onlineReady||finished||data.index<0||data.index>=board.length||board[data.index])return;
   play(data.index,true);
  }
 });
 connection.on('close',()=>{
  onlineReady=false;updateStatus('Друг отключился.');
  $('netStatus').textContent='Соединение закрыто.';
  render();
 });
 connection.on('error',()=>{$('netStatus').textContent='Ошибка соединения'});
}
function copyRoom(){
 const text=room;
 if(navigator.clipboard&&navigator.clipboard.writeText){
  navigator.clipboard.writeText(text).then(()=>toast('Код скопирован!')).catch(()=>toast('Код: '+text));
 }else toast('Код комнаты: '+text);
}
newGame();
</script>
</body>
</html>
