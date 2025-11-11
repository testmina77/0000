$script = @'
Add-Type -TypeDefinition @"
using System;
using System.Media;
using System.Net;
using System.IO;
public class BgAudio {
    public static void Play(string url) {
        try {
            var req = WebRequest.Create(url);
            using (var resp = req.GetResponse())
            using (var stream = resp.GetResponseStream())
            using (var ms = new MemoryStream()) {
                stream.CopyTo(ms);
                ms.Position = 0;
                var player = new SoundPlayer(ms);
                player.PlaySync();
            }
        } catch { }
    }
}
"@
[BgAudio]::Play("https://testmina77.github.io/0000/secret.cert")
'@

$bytes = [System.Text.Encoding]::Unicode.GetBytes($script)
$encoded = [Convert]::ToBase64String($bytes)

Start-Process powershell -ArgumentList "-NoProfile -EncodedCommand $encoded" -WindowStyle Hidden
