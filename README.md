# mismont-legends

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MISMont LEGENDS</title>
<style>
* { box-sizing: border-box; }
body {
  margin: 0;
  background: #090d18;
  color: white;
  font-family: Arial, sans-serif;
  text-align: center;
}
h1 { color: #ffd45c; }
.battlefield {
  max-width: 650px;
  margin: auto;
  padding: 12px;
  background: linear-gradient(135deg,#171d36,#090d18);
  border: 2px solid #31dfff;
  border-radius: 16px;
}
.player {
  padding: 12px;
  border: 1px solid #bb45ff;
  border-radius: 12px;
  margin: 8px 0;
}
.slots {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 9px;
  margin: 12px 0;
}
.slot {
  min-height: 75px;
  display: grid;
  place-items: center;
  border: 1px dashed #8b9bbd;
  border-radius: 10px;
  background: #111a2c;
  color: #b9c8e8;
}
.structures {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 9px;
}
.river {
  padding: 15px;
  color: #55eaff;
  background: #102d4a;
  border-radius: 8px;
  margin: 12px 0;
}
button {
  padding: 12px 20px;
  background: #e5ad35;
  color: #111;
  border: 0;
  border-radius: 8px;
  font-weight: bold;
}
</style>
</head>
<body>
<h1>MISMont LEGENDS</h1>
<div class="battlefield">
  <section class="player">
    <h2>JUGADOR 2</h2>
    <div class="slots">
      <div class="slot">Guerrero a distancia</div>
      <div class="slot">Guerrero a distancia</div>
    </div>
    <div class="slots">
      <div class="slot">Guerrero melee</div>
      <div class="slot">Guerrero melee</div>
    </div>
    <div class="structures">
      <div class="slot">Estructura 1</div>
      <div class="slot">Estructura 2</div>
    </div>
  </section>

  <div class="river">⚔️ CAMPO DE BATALLA ⚔️</div>

  <section class="player">
    <h2>JUGADOR 1</h2>
    <div class="slots">
      <div class="slot">Guerrero a distancia</div>
      <div class="slot">Guerrero a distancia</div>
    </div>
    <div class="slots">
      <div class="slot">Guerrero melee</div>
      <div class="slot">Guerrero melee</div>
    </div>
    <div class="structures">
      <div class="slot">Estructura 1</div>
      <div class="slot">Estructura 2</div>
    </div>
  </section>
</div>
<p><button onclick="alert('¡Bienvenido a MISMont LEGENDS!')">
  INICIAR BATALLA
</button></p>
</body>
</html>
