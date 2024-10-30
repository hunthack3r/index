```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hacked Banner</title>
    <style>
        /* Genel Ayarlar */
        body {
            background-color: black;
            color: crimson;
            font-family: 'Courier New', monospace;
            overflow: hidden;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }

        /* Arka Planda Kayan Kodlar */
        .background-code {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            color: rgba(0, 255, 0, 0);
            font-size: 16px;
            line-height: 1.5;
            overflow: hidden;
            white-space: nowrap;
            animation: scroll 10s linear infinite;
            z-index: -1;
            text-shadow: 0 0 3px green, 0 0 3px crimson;
        }

        @keyframes scroll {
            from { transform: translateY(100%); }
            to { transform: translateY(-100%); }
        }

        /* Ana İçerik */
        .skull {
            font-size: 120px;
            color: crimson;
            animation: blink 0.8s infinite alternate;
            margin-bottom: 20px;
            text-shadow: 0 0 20px crimson, 0 0 30px red, 0 0 40px darkred;
        }

        @keyframes blink {
            0% { opacity: 1; }
            100% { opacity: 0.1; }
        }

        .hacked-text {
            color: crimson;
            font-size: 48px;
            font-weight: bold;
            text-shadow: 0 0 10px crimson, 0 0 20px red, 0 0 30px darkred;
            margin: 0;
            animation: flicker 1.2s infinite alternate;
        }

        @keyframes flicker {
            0% { opacity: 1; }
            100% { opacity: 0.2; }
        }

        .compromised-text {
            color: red;
            font-size: 28px;
            text-shadow: 0 0 10px red, 0 0 20px darkred, 0 0 30px black;
            margin: 10px 0;
            animation: flicker 1.5s infinite alternate;
        }

        /* Marquee Uyarı Çubuğu */
        .warning-bar {
            background-color: darkred;
            color: white;
            font-size: 20px;
            padding: 10px;
            width: 100%;
            text-align: center;
            position: fixed;
            bottom: 0;
            left: 0;
            font-weight: bold;
            overflow: hidden;
            text-transform: uppercase;
            text-shadow: 0 0 5px black;
        }

        .marquee {
            display: inline-block;
            animation: marquee 12s linear infinite;
            white-space: nowrap;
        }

        @keyframes marquee {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
    </style>
</head>
<body>
    <!-- Arka planda kayan programlama kodları -->
  <div class="background-code">
      print("DedCrowd")<br>
      System.out.println("DedCrowd");<br>
      Console.WriteLine("DedCrowd");<br>
      echo "DedCrowd";<br>
      printf("DedCrowd");<br>
      cout << "DedCrowd" << endl;<br>
      document.write("DedCrowd");<br>
      alert("DedCrowd");<br>
      var name = "DedCrowd"; console.log(name);<br>
      DedCrowd.execute();<br>
      # DedCrowd in Python<br>
      puts "DedCrowd"<br>
      - (void) printDedCrowd { NSLog(@"DedCrowd"); }<br>
      Dim Name As String = "DedCrowd" <br>
      Write-Output "DedCrowd"<br>
      <span style="color: rgba(255, 0, 0, 0.2);">DedCrowd</span><br>
      BEGIN DedCrowd; END;<br>
      $dedcrowd = "DedCrowd"; print $dedcrowd;<br>
      <script>document.body.innerHTML += "DedCrowd";</script><br>
      SELECT * FROM users WHERE name = 'DedCrowd';<br>
      for(int i=0; i<10; i++) { printf("DedCrowd"); }<br>
      func display() { print("DedCrowd") }<br>
      DedCrowd -> make();<br>
      with open("file.txt", "w") as f: f.write("DedCrowd")<br>
      <span style="color: rgba(255, 0, 0, 0.2);">const name = 'DedCrowd';</span><br>
      data = { "username": "DedCrowd" }<br>
      $sql = "INSERT INTO logs VALUES ('DedCrowd');";<br>
      DedCrowd.printAll();<br>
      <marquee>DedCrowd</marquee><br>
      print <<-EOF\nDedCrowd\nEOF<br>
      [DedCrowd] -> new;<br>
      DedCrowd.add("DedCrowd")<br>
      function display() { echo "DedCrowd"; }<br>
      echo '<h1>DedCrowd</h1>';<br>
      int main() { printf("DedCrowd"); return 0; }<br>
  </div>

    <!-- Ana içerik -->
    <div class="skull">☠️</div>
    <h1 class="hacked-text">Hacked By DedCrowd</h1>
    <p class="compromised-text">System Compromised</p>

    <!-- Marquee Uyarı Çubuğu -->
    <div class="warning-bar">
        <div class="marquee">WARNING: Your data is at risk! Secure it before it's too late. | WARNING: Your data is at risk! Secure it before it's too late. | </div>
    </div>
</body>
</html>

```
