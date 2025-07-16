<!-- form.php -->
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>แบบฟอร์มนักเรียน</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="container mt-5">
  <h2>แบบฟอร์มกรอกข้อมูลนักเรียน</h2>
  <form action="display.php" method="get">
    <div class="mb-3">
      <label>ชื่อ-นามสกุล:กิ่งกาญจน์ รวมพล</label>
      <input type="text" name="name" class="form-control" required>
    </div>
    <div class="mb-3">
      <label>ชั้น:ม.6/9</label>
      <input type="text" name="class" class="form-control" required>
    </div>
    <div class="mb-3">
      <label>เลขที่:39</label>
      <input type="number" name="no" class="form-control" required>
    </div>
    <div class="mb-3">
      <label>แผนการเรียน</label>
      <select name="plan" class="form-select">
        <option value="เทคโนโลยี">เทคโนโลยี</option>
      </select>
    </div>
    <div class="mb-3">
      <label>เพศ</label><br>
      <input type="radio" name="gender" value="หญิง"> หญิง
    </div>
    <button type="submit" class="btn btn-primary">ส่งข้อมูล</button>
  </form>
</body>
</html>
