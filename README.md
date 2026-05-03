<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Satu Hal Penting</title>
    <script src="https://tailwindcss.com"></script>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .gradient-text {
            background: linear-gradient(90deg, #ff4d4d, #f9cb28);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-black text-white flex items-center justify-center min-h-screen p-6">

    <div class="max-w-md w-full text-center space-y-8 animate-fade-in">
        <h1 class="text-4xl font-bold leading-tight">
            Saya jarang salah soal <span class="gradient-text">intuisi.</span>
        </h1>

        <div class="space-y-4 text-gray-400 text-lg">
            <p class="animate-pulse">Satu pesan untuk kamu...</p>
            
            <div class="bg-zinc-900 p-6 rounded-2xl border border-zinc-800 text-left">
                <p class="text-white italic leading-relaxed">
                    "Dunia penuh dengan orang yang berusaha jadi luar biasa. Tapi kamu? Kamu punya ketenangan yang bikin semua kebisingan di kepala saya berhenti. Itu jauh lebih langka daripada sekadar cantik."
                </p>
            </div>
        </div>

        <button onclick="luluh()" class="bg-white text-black px-8 py-3 rounded-full font-bold hover:scale-105 transition-transform">
            Klik kalau kamu setuju
        </button>

        <p id="response" class="hidden text-orange-400 font-medium">
            Ternyata intuisi saya benar. Kita harus bicara lebih serius setelah ini.
        </p>
    </div>

    <script>
        function luluh() {
            document.getElementById('response').classList.remove('hidden');
        }
    </script>
</body>
</html>

