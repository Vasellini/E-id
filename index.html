<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>ID Profile</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: #f5f5f5;
}

/* HEADER */
.header {
  display: flex;
  align-items: center;
  padding: 10px;
  background: white;
  border-bottom: 1px solid #ddd;
}

.menu {
  font-size: 24px;
  margin-right: 10px;
  cursor: pointer;
}

.profile-mini {
  display: flex;
  align-items: center;
}

.profile-mini img {
  width: 40px;
  border-radius: 5px;
  margin-right: 10px;
}

/* TABS */
.tabs {
  display: flex;
  justify-content: space-around;
  background: white;
  padding: 10px 0;
}

.tab {
  text-align: center;
  cursor: pointer;
  color: gray;
}

.tab.active {
  color: #00a8a8;
  border-bottom: 3px solid #00a8a8;
}

/* CONTENT */
.section {
  display: none;
  padding: 20px;
}

.section.active {
  display: block;
}

/* PROFILE CARD */
.card {
  background: white;
  padding: 20px;
  border-radius: 15px;
  text-align: center;
}

.card img {
  width: 120px;
  border-radius: 10px;
}

.info-row {
  margin-top: 15px;
}

button {
  margin-top: 15px;
  padding: 10px;
  border: none;
  border-radius: 8px;
  background: #00a8a8;
  color: white;
  cursor: pointer;
}

/* INPUTS */
input {
  width: 90%;
  padding: 8px;
  margin: 5px;
}
</style>
</head>

<body>

<!-- HEADER -->
<div class="header">
  <div class="menu">☰</div>
  <div class="profile-mini">
    <img id="miniPic" src="https://via.placeholder.com/40">
    <div>
      <div id="miniName"></div>
      <small id="miniId">0388308L</small>
    </div>
  </div>
</div>

<!-- TABS -->
<div class="tabs">
  <div class="tab active" onclick="showTab('info')">My Info</div>
  <div class="tab" onclick="showTab('privacy')">Privacy & Security</div>
  <div class="tab" onclick="showTab('help')">Help</div>
</div>

<!-- MY INFO -->
<div id="info" class="section active">
  <div class="card">
    <img id="profilePic" src="https://via.placeholder.com/120">

    <h2 id="name"></h2>
    <p id="dob"></p>

    <div class="info-row">
      <p id="email"></p>
      <p id="phone"></p>
    </div>

    <button onclick="toggleEdit()">Edit</button>
    <button onclick="refreshPage()">Refresh</button>

    <div id="editForm" style="display:none;">
      <input id="editName" placeholder="Name">
      <input id="editDob" placeholder="DOB">
      <input id="editEmail" placeholder="Email">
      <input id="editPhone" placeholder="Phone">
      <button onclick="saveData()">Save</button>
    </div>
  </div>
</div>

<!-- PRIVACY -->
<div id="privacy" class="section">
  <div class="card">
    <h2>Privacy & Security</h2>
    <p>You can manage your data here.</p>
    <button onclick="clearData()">Clear Saved Data</button>
  </div>
</div>

<!-- HELP -->
<div id="help" class="section">
  <div class="card">
    <h2>Help</h2>
    <p>If something isn’t working, refresh the page or contact support.</p>
  </div>
</div>

<script>
const defaultData = {
  name: "Jake Fasanelli Simiana",
  dob: "11/11/2008",
  email: "example@gmail.com",
  phone: "+356 77007622"
};

function loadData() {
  const data = JSON.parse(localStorage.getItem("profile")) || defaultData;

  document.getElementById("name").innerText = data.name;
  document.getElementById("dob").innerText = data.dob;
  document.getElementById("email").innerText = data.email;
  document.getElementById("phone").innerText = data.phone;

  document.getElementById("miniName").innerText = data.name;

  document.getElementById("editName").value = data.name;
  document.getElementById("editDob").value = data.dob;
  document.getElementById("editEmail").value = data.email;
  document.getElementById("editPhone").value = data.phone;
}

function toggleEdit() {
  const form = document.getElementById("editForm");
  form.style.display = form.style.display === "none" ? "block" : "none";
}

function saveData() {
  const data = {
    name: editName.value,
    dob: editDob.value,
    email: editEmail.value,
    phone: editPhone.value
  };

  localStorage.setItem("profile", JSON.stringify(data));
  loadData();
  toggleEdit();
}

function showTab(tab) {
  document.querySelectorAll(".section").forEach(s => s.classList.remove("active"));
  document.querySelectorAll(".tab").forEach(t => t.classList.remove("active"));

  document.getElementById(tab).classList.add("active");
  event.target.classList.add("active");
}

function refreshPage() {
  location.reload();
}

function clearData() {
  localStorage.removeItem("profile");
  loadData();
  alert("Data cleared");
}

loadData();
</script>

</body>
</html>
