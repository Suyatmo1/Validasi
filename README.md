
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kelengkapan Checklist dan Validasi Checklist HD785-7</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #dce35b, #45b649);
      color: #333;
      min-height: 100vh;
    }
    .container { 
      background-color: rgba(255,255,255,0.95);
      padding: 2rem;
      border-radius: 15px;
      margin-top: 2rem;
      box-shadow: 0 8px 24px rgba(0,0,0,0.2);
    }
    .tab-pane { display: none; }
    .tab-pane.active { display: block; }
    footer {
      text-align: center;
      margin-top: 2rem;
      color: #333;
    }
    .nav-link { cursor: pointer; }
    .form-control, .btn {
      border-radius: 10px;
    }
    .card {
      background-color: #f9f9f9;
      color: #333;
    }
  </style>
</head>
<body>
  <div class="container">
    <ul class="nav nav-tabs mb-3">
      <li class="nav-item"><a class="nav-link" onclick="ubahTab('login')">Login</a></li>
      <li class="nav-item"><a class="nav-link" onclick="ubahTab('checklist')">Checklist</a></li>
      <li class="nav-item"><a class="nav-link" onclick="ubahTab('riwayat')">Riwayat</a></li>
      <li class="nav-item"><a class="nav-link" onclick="ubahTab('logout')">Logout</a></li>
      <li class="nav-item"><a class="nav-link" onclick="ubahTab('sandi')">Ubah Sandi</a></li>
    </ul>

    <div class="tab-content">
      <div class="tab-pane active" id="login">
        <h3>Login Aplikasi</h3>
        <div class="alert alert-info">Selamat datang Team Weel di Validasi Checklist. Tetap Semangat, Jangan Lupa Bahagia, Selalu Berdoa, Jaga Kesehatan dan Keselamatan Disetiap Pekerjaan <strong></strong></div>
        <input type="password" id="loginPass" class="form-control mb-2" placeholder="Masukkan sandi">
        <button class="btn btn-primary" onclick="doLogin()">Login</button>
      </div>

      <div class="tab-pane" id="checklist">
        <h3>Final Inspection QA7</h3>
        <input type="text" class="form-control mb-2" placeholder="Kode Unit" id="unit">
        <input type="text" class="form-control mb-2" placeholder="HM Unit" id="jam">
        <input type="date" class="form-control mb-2" id="tanggal">
        <input type="text" class="form-control mb-2" placeholder="Nama Mekanik" id="mekanik">
        <input type="text" class="form-control mb-2" placeholder="Nama Grup Leader" id="leader">
        <textarea class="form-control mb-2" placeholder="Catatan" id="catatan"></textarea>
        <label class="form-label">Upload Gambar/Foto :</label>
        <input type="file" class="form-control mb-2" id="gambar" multiple accept="image/*">
        <input type="file" class="form-control mb-2" id="gambar" multiple accept="image/*">
        <input type="file" class="form-control mb-2" id="gambar" multiple accept="image/*">
        <input type="file" class="form-control mb-2" id="gambar" multiple accept="image/*">
        <input type="file" class="form-control mb-2" id="gambar" multiple accept="image/*">
        <!-- Midlife Komponen Section -->
<div class="midlife-komponen">
  <h3>Midlife Komponen</h3>
  <form>
    <label><input type="checkbox" name="midlife" value="FIRE SUSPRESSION"> FIRE SUSPRESSION (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="ALTERNATOR"> ALTERNATOR (Interval: 10.000)</label><br>
    <label><input type="checkbox" name="midlife" value="STARTING MOTOR UP 1"> STARTING MOTOR UP (Interval: 10.000)</label><br>
    <label><input type="checkbox" name="midlife" value="STARTING MOTOR UP 2"> STARTING MOTOR UP (Interval: 10.000)</label><br>
    <label><input type="checkbox" name="midlife" value="WATER PUMP"> WATER PUMP (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="TENSION PULLEY"> TENSION PULLEY (Interval: 15.000)</label><br>
    <label><input type="checkbox" name="midlife" value="STEERING CYLINDER RH"> STEERING CYLINDER RH (Interval: 19.000)</label><br>
    <label><input type="checkbox" name="midlife" value="STEERING CYLINDER LH"> STEERING CYLINDER LH (Interval: 19.000)</label><br>
    <label><input type="checkbox" name="midlife" value="VALVE SUSPENSION"> VALVE SUSPENSION (Interval: 8.000)</label><br>
    <label><input type="checkbox" name="midlife" value="INJECTOR"> INJECTOR (Interval: 15.000)</label><br>
    <label><input type="checkbox" name="midlife" value="DAMPER ENGINE"> DAMPER ENGINE (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="EVAPORATOR"> EVAPORATOR (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="STEERING VALVE"> STEERING VALVE (Interval: 8.000)</label><br>
    <label><input type="checkbox" name="midlife" value="BUSHING TORQ ROD & RADIUS ROD"> BUSHING TORQ ROD & RADIUS ROD (Interval: 19.000)</label><br>
    <label><input type="checkbox" name="midlife" value="ADJUST VALVE"> ADJUST VALVE (Interval: 7.500)</label><br>
    <label><input type="checkbox" name="midlife" value="FRONT SUSPENSION RH"> FRONT SUSPENSION RH (Interval: 16.000)</label><br>
    <label><input type="checkbox" name="midlife" value="FRONT SUSPENSION LH"> FRONT SUSPENSION LH (Interval: 16.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REAR SUSPENSION RH"> REAR SUSPENSION RH (Interval: 16.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REAR SUSPENSION LH"> REAR SUSPENSION LH (Interval: 16.000)</label><br>
    <label><input type="checkbox" name="midlife" value="HOIST CYLINDER RH"> HOIST CYLINDER RH (Interval: 25.000)</label><br>
    <label><input type="checkbox" name="midlife" value="HOIST CYLINDER LH"> HOIST CYLINDER LH (Interval: 25.000)</label><br>
    <label><input type="checkbox" name="midlife" value="ADJUST DIFFERENTIAL"> ADJUST DIFFERENTIAL (Interval: 23.000)</label><br>
    <label><input type="checkbox" name="midlife" value="TURBO CHARGER RH"> TURBO CHARGER RH (Interval: 20.000)</label><br>
    <label><input type="checkbox" name="midlife" value="TURBO CHARGER LH"> TURBO CHARGER LH (Interval: 20.000)</label><br>
    <label><input type="checkbox" name="midlife" value="CLEANING FUEL TANK"> CLEANING FUEL TANK (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="CYLINDER HEAD"> CYLINDER HEAD (Interval: 28.000)</label><br>
    <label><input type="checkbox" name="midlife" value="RUBBER CUSHION T/M"> RUBBER CUSHION T/M (Interval: 24.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REBUSHING STEERING LINK"> REBUSHING STEERING LINK (Interval: 19.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REBUSHING FRONT AXLE"> REBUSHING FRONT AXLE (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REBUSHING REAR AXLE"> REBUSHING REAR AXLE (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REBUSHING VESSEL"> REBUSHING VESSEL (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="COMPRESSOR + CLUTCH AC"> COMPRESSOR + CLUTCH AC (Interval: 8.000)</label><br>
    <label><input type="checkbox" name="midlife" value="AIR COMPRESSOR"> AIR COMPRESSOR (Interval: 8.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REHOSE AC"> REHOSE AC (Interval: 24.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REHOSE FRONT BRAKE COOLING"> REHOSE FRONT BRAKE COOLING (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REHOSE REAR BRAKE COOLING"> REHOSE REAR BRAKE COOLING (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REHOSE HOIST CYLINDER"> REHOSE HOIST CYLINDER (Interval: 8.000)</label><br>
    <label><input type="checkbox" name="midlife" value="REHOSE STEERING VALVE"> REHOSE STEERING VALVE (Interval: 8.000)</label><br>
    <label><input type="checkbox" name="midlife" value="MOTOR BLOWER AC"> MOTOR BLOWER AC (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="OIL PUMP"> OIL PUMP (Interval: 18.000)</label><br>
    <label><input type="checkbox" name="midlife" value="AUTOLUB"> AUTOLUB (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="OPERATOR SEAT"> OPERATOR SEAT (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="VISCOUS MOUNTING CABIN"> VISCOUS MOUNTING CABIN (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="COMMON RAIL SENSOR RH"> COMMON RAIL SENSOR RH (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="COMMON RAIL SENSOR LH"> COMMON RAIL SENSOR LH (Interval: 6.000)</label><br>
    <label><input type="checkbox" name="midlife" value="P/T PUMP"> P/T PUMP (Interval: 12.000)</label><br>
    <label><input type="checkbox" name="midlife" value="STEERING PUMP"> STEERING PUMP (Interval: 24.000)</label><br>
    <label><input type="checkbox" name="midlife" value="T/M PUMP"> T/M PUMP (Interval: 24.000)</label><br>
    <label><input type="checkbox" name="midlife" value="B/C PUMP"> B/C PUMP (Interval: 24.000)</label><br>
    <label><input type="checkbox" name="midlife" value="HYDRAULIC PUMP"> HYDRAULIC PUMP (Interval: 25.000)</label><br>
    <label><input type="checkbox" name="midlife" value="CLEANING RADIATOR & AF COOLER"> CLEANING RADIATOR & AF COOLER (Interval: 20.000)</label><br>
  </form>
</div>

        <button class="btn btn-success" onclick="simpanChecklist()">Simpan Checklist</button>
      </div>

      <div class="tab-pane" id="riwayat">
        <h3>Riwayat Checklist</h3>
        <input type="text" class="form-control mb-2" id="cari" placeholder="Cari berdasarkan unit atau catatan..." oninput="tampilkanRiwayat()">
        <div id="listRiwayat"></div>
      </div>

      <div class="tab-pane" id="sandi">
        <h3>Ganti Sandi</h3>
        <input type="password" class="form-control mb-2" id="sandiBaru" placeholder="Sandi Baru">
        <button class="btn btn-warning" onclick="gantiSandi()">Ganti</button>
      </div>

      <div class="tab-pane" id="logout">
        <h3>Logout</h3>
        <button class="btn btn-danger" onclick="logout()">Logout</button>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 Program Kelengkapan dan Validasi Checklist HD785-7 By; Suyatmo (Nrp:61140012) / IO University (Nim:049026401)
  </footer>

  <script>
    let dataChecklist = JSON.parse(localStorage.getItem('checklist')) || [];
    let sandi = localStorage.getItem('sandi') || 'admin';
    let sudahLogin = false;

    function doLogin() {
      const pass = document.getElementById('loginPass').value;
      if (pass === sandi) {
        sudahLogin = true;
        ubahTab('checklist');
      } else {
        alert('Sandi salah!');
      }
    }

    function simpanChecklist() {
      const unit = document.getElementById('unit').value;
      const jam = document.getElementById('jam').value;
      const tanggal = new Date().toISOString().split('T')[0];
      const mekanik = document.getElementById('mekanik').value;
      const leader = document.getElementById('leader').value;
      const catatan = document.getElementById('catatan').value;
      const files = document.getElementById('gambar').files;
      if (!unit || !jam || !mekanik || !leader || !catatan || files.length === 0) {
        alert('Lengkapi semua data!');
        return;
      }

      const images = [];
      let loaded = 0;

      if (files.length > 5) {
        alert('Maksimal upload 5 file gambar.');
        return;
      }

      Array.from(files).forEach(file => {
        const reader = new FileReader();
        reader.onload = function(e) {
          images.push(e.target.result);
          loaded++;
          if (loaded === files.length) {
            dataChecklist.push({ unit, jam, tanggal, mekanik, leader, catatan, gambar: images });
            localStorage.setItem('checklist', JSON.stringify(dataChecklist));
            alert('Checklist disimpan!');
            document.querySelectorAll('#checklist input, #checklist textarea').forEach(el => el.value = '');
            tampilkanRiwayat();
          }
        };
        reader.readAsDataURL(file);
      });
    }

    function tampilkanRiwayat() {
      const cari = document.getElementById('cari')?.value?.toLowerCase() || '';
      const hasil = dataChecklist.map((d, index) => ({...d, index})).filter(d => d.unit.toLowerCase().includes(cari) || d.catatan.toLowerCase().includes(cari));
      document.getElementById('listRiwayat').innerHTML = hasil.map(d => `
        <div class='card mb-2'>
          <div class='card-body'>
            <h5>${d.unit}</h5>
            <p>HM: ${d.jam}, Tanggal: ${d.tanggal}</p>
            <p>Mekanik: ${d.mekanik}, Leader: ${d.leader}</p>
            <p>Catatan: ${d.catatan}</p>
            ${d.gambar.map(src => `<img src='${src}' style='max-width:800px; margin-right:5px;'>`).join('')}
            <button class='btn btn-sm btn-danger mt-2' onclick='hapusRiwayat(${d.index})'>Hapus</button>
          </div>
        </div>
      `).join('');
    }

    function hapusRiwayat(index) {
      if (confirm('Yakin ingin menghapus riwayat ini?')) {
        dataChecklist.splice(index, 1);
        localStorage.setItem('checklist', JSON.stringify(dataChecklist));
        tampilkanRiwayat();
      }
    }

    function gantiSandi() {
      const baru = document.getElementById('sandiBaru').value;
      if (!baru) return alert('Sandi tidak boleh kosong!');
      localStorage.setItem('sandi', baru);
      sandi = baru;
      alert('Sandi berhasil diganti!');
    }

    function logout() {
      sudahLogin = false;
      ubahTab('login');
    }

    function ubahTab(id) {
      if (!sudahLogin && id !== 'login') {
        alert('Harap login terlebih dahulu');
        id = 'login';
      }
      document.querySelectorAll('.tab-pane').forEach(p => p.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }

    tampilkanRiwayat();
  </script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
