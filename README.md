<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monitoreo de Agua - Casa de Danna</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        .water-animation {
            background: linear-gradient(90deg, #e0f7fa, #80deea, #4dd0e1, #26c6da);
            background-size: 400% 400%;
            animation: gradient 15s ease infinite;
        }
        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
    </style>
</head>
<body class="bg-gray-50">
    <header class="water-animation text-white py-6">
        <div class="container mx-auto px-4">
            <h1 class="text-3xl font-bold">Monitoreo de Agua</h1>
            <p class="mt-2">Casa de Danna - Reduciendo la huella hídrica</p>
        </div>
    </header>

    <main class="container mx-auto px-4 py-8">
        <section class="mb-12">
            <div class="bg-white rounded-lg shadow-md p-6">
                <h2 class="text-2xl font-semibold text-blue-600 mb-4">Consumo en Tiempo Real</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-blue-50 p-4 rounded-lg">
                        <h3 class="font-medium text-blue-800">Caudal Actual</h3>
                        <p class="text-3xl font-bold mt-2">8.5 <span class="text-lg">L/min</span></p>
                    </div>
                    <div class="bg-green-50 p-4 rounded-lg">
                        <h3 class="font-medium text-green-800">Consumo Hoy</h3>
                        <p class="text-3xl font-bold mt-2">120 <span class="text-lg">Litros</span></p>
                    </div>
                    <div class="bg-yellow-50 p-4 rounded-lg">
                        <h3 class="font-medium text-yellow-800">Alerta</h3>
                        <p class="text-xl font-bold mt-2 text-green-600">Todo normal</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-semibold text-blue-600 mb-4">Gráficos de Consumo</h2>
            <div class="bg-white rounded-lg shadow-md p-6">
                <div class="h-64 bg-gray-100 rounded flex items-center justify-center">
                    <p class="text-gray-500">Gráfico de consumo aparecerá aquí</p>
                </div>
            </div>
        </section>

        <section>
            <h2 class="text-2xl font-semibold text-blue-600 mb-4">Consejos para Ahorrar Agua</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="font-medium text-blue-800 mb-2">Duchas</h3>
                    <p>Intenta reducir el tiempo de ducha a 5 minutos. Una ducha promedio usa 12 litros por minuto.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="font-medium text-blue-800 mb-2">Grifos</h3>
                    <p>Cierra el grifo mientras te lavas los dientes o las manos. Un grifo abierto puede usar hasta 6 litros por minuto.</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto px-4 text-center">
            <p>Sistema IoT de Monitoreo de Agua - Casa de Danna</p>
            <p class="mt-2 text-sm text-gray-400">© 2025 Todos los derechos reservados</p>
        </div>
    </footer>
</body>
</html>
