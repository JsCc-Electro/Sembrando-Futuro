<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infografía: Fundación Sembrando Futuro en Rioblanco</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
    </style>
</head>
<body class="bg-[#F0F4F8]">
    <div class="container mx-auto p-4 md:p-8">

        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-black text-[#003B73]">Fundación Sembrando Futuro</h1>
            <p class="text-xl md:text-2xl text-[#0074D9] mt-2">Transformando Vidas y Construyendo Paz en Rioblanco, Tolima</p>
        </header>

        <main class="space-y-12">
            
            <section id="diagnostico" class="bg-white rounded-lg shadow-lg p-6 md:p-8">
                <h2 class="text-3xl font-bold text-[#003B73] mb-6 text-center">Diagnóstico de Rioblanco: Un Territorio de Resiliencia</h2>
                <p class="text-center text-lg text-gray-700 mb-8 max-w-3xl mx-auto">Rioblanco es un municipio con una historia compleja, marcado por el conflicto armado pero con una inmensa capacidad de superación. Entender su realidad es clave para nuestra misión.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 text-center">
                    <div class="bg-[#EBF5FF] p-6 rounded-lg">
                        <p class="text-5xl font-black text-[#0074D9]">23,429</p>
                        <p class="text-lg text-[#003B73] mt-2">Habitantes (Proyección 2024)</p>
                    </div>
                    <div class="bg-[#EBF5FF] p-6 rounded-lg">
                        <p class="text-5xl font-black text-[#0074D9]">62.5%</p>
                        <p class="text-lg text-[#003B73] mt-2">Población Rural</p>
                    </div>
                    <div class="bg-[#EBF5FF] p-6 rounded-lg">
                        <p class="text-5xl font-black text-[#0074D9]">~4,383</p>
                        <p class="text-lg text-[#003B73] mt-2">Adultos Mayores (Estimado)</p>
                    </div>
                </div>
            </section>
            
            <section id="conflicto" class="bg-white rounded-lg shadow-lg p-6 md:p-8">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div class="md:col-span-1">
                        <h3 class="text-2xl font-bold text-[#003B73] mb-4">El Impacto del Conflicto Armado</h3>
                        <p class="text-gray-700 text-lg mb-4">La estadística más contundente de Rioblanco es el porcentaje de su población que ha sido víctima directa del conflicto. Este dato no es solo un número, es el eje central de nuestra intervención psicosocial y el motor para construir un futuro en paz.</p>
                        <div class="bg-[#FFECB3] p-4 rounded-lg text-center">
                            <p class="text-6xl font-black text-[#FFA000]">10,580</p>
                            <p class="text-xl text-[#E65100]">Personas registradas como víctimas</p>
                        </div>
                    </div>
                    <div class="md:col-span-1">
                         <div class="chart-container h-80 md:h-96">
                            <canvas id="victimasChart"></canvas>
                        </div>
                    </div>
                </div>
            </section>

            <section id="poblacion" class="bg-white rounded-lg shadow-lg p-6 md:p-8">
                <h2 class="text-3xl font-bold text-[#003B73] mb-8 text-center">Nuestras Poblaciones Prioritarias</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="text-center p-6 bg-[#EBF5FF] rounded-lg">
                        <div class="text-6xl mb-4">👵</div>
                        <h3 class="text-2xl font-bold text-[#003B73]">Adultos Mayores</h3>
                        <p class="text-gray-700 mt-2">Sobrevivientes del conflicto que portan la memoria histórica. Son nuestra máxima prioridad, buscando dignificar su vejez.</p>
                    </div>
                    <div class="text-center p-6 bg-[#EBF5FF] rounded-lg">
                        <div class="text-6xl mb-4">👩</div>
                        <h3 class="text-2xl font-bold text-[#003B73]">Mujeres</h3>
                        <p class="text-gray-700 mt-2">Pilares de la resiliencia familiar. Empoderarlas es reconstruir el tejido social y fomentar la paz sostenible.</p>
                    </div>
                    <div class="text-center p-6 bg-[#EBF5FF] rounded-lg">
                        <div class="text-6xl mb-4">👧👦</div>
                        <h3 class="text-2xl font-bold text-[#003B73]">Niños, Niñas y Adolescentes</h3>
                        <p class="text-gray-700 mt-2">Crecen en un entorno de alto riesgo. Creamos entornos protectores para romper ciclos de violencia.</p>
                    </div>
                </div>
            </section>
            
            <section id="proyecto-macro" class="bg-[#003B73] text-white rounded-lg shadow-lg p-6 md:p-8">
                <h2 class="text-3xl font-bold mb-6 text-center">Proyecto Macro: Hogar Gerontológico de Rioblanco</h2>
                <p class="text-center text-lg text-gray-200 mb-8 max-w-3xl mx-auto">Nuestra iniciativa más ambiciosa es una respuesta directa a las necesidades del territorio: un refugio para la dignidad, el cuidado y la sanación de nuestros mayores.</p>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h3 class="text-2xl font-bold text-[#79BDEE] mb-4">Componentes Estratégicos</h3>
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <div class="bg-[#0074D9] rounded-full h-8 w-8 flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-white font-bold">1</span>
                                </div>
                                <div>
                                    <h4 class="font-bold">Infraestructura Digna</h4>
                                    <p class="text-gray-300">Construcción o adecuación de un espacio seguro, accesible y acogedor.</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="bg-[#0074D9] rounded-full h-8 w-8 flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-white font-bold">2</span>
                                </div>
                                <div>
                                    <h4 class="font-bold">Dotación Completa</h4>
                                    <p class="text-gray-300">Equipamiento especializado para el cuidado médico, la terapia y el bienestar.</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="bg-[#0074D9] rounded-full h-8 w-8 flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-white font-bold">3</span>
                                </div>
                                <div>
                                    <h4 class="font-bold">Talento Humano Calificado</h4>
                                    <p class="text-gray-300">Equipo interdisciplinario con enfoque en gerontología y atención psicosocial.</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="bg-[#0074D9] rounded-full h-8 w-8 flex items-center justify-center mr-4 flex-shrink-0">
                                    <span class="text-white font-bold">4</span>
                                </div>
                                <div>
                                    <h4 class="font-bold">Sostenibilidad Financiera</h4>
                                    <p class="text-gray-300">Modelo mixto con fondos públicos (PDET, ZOMAC) y cooperación internacional.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div>
                        <div class="chart-container h-80 md:h-96">
                            <canvas id="impactoChart"></canvas>
                        </div>
                    </div>
                </div>
            </section>

        </main>

        <footer class="text-center mt-12 pt-8 border-t border-gray-300">
            <p class="text-lg font-bold text-[#003B73]">Fundación para la Promoción y el Desarrollo Integral Humano y Social Sembrando Futuro</p>
            <p class="text-gray-600">NIT: 900485812-1 | Rioblanco, Tolima</p>
        </footer>

    </div>

    <script>
        const tooltipTitleCallback = (tooltipItems) => {
            const item = tooltipItems[0];
            let label = item.chart.data.labels[item.dataIndex];
            if (Array.isArray(label)) {
                return label.join(' ');
            }
            return label;
        };
        
        const wrapLabel = (label) => {
            const maxLength = 16;
            if (label.length <= maxLength) return label;
            const words = label.split(' ');
            const lines = [];
            let currentLine = '';
            words.forEach(word => {
                if ((currentLine + word).length > maxLength) {
                    lines.push(currentLine.trim());
                    currentLine = '';
                }
                currentLine += word + ' ';
            });
            lines.push(currentLine.trim());
            return lines;
        };

        const victimasData = {
            totalPoblacion: 23429,
            victimas: 10580,
        };
        victimasData.noVictimas = victimasData.totalPoblacion - victimasData.victimas;
        const porcentajeVictimas = (victimasData.victimas / victimasData.totalPoblacion) * 100;

        const ctxVictimas = document.getElementById('victimasChart').getContext('2d');
        new Chart(ctxVictimas, {
            type: 'doughnut',
            data: {
                labels: [`Población Víctima del Conflicto (${porcentajeVictimas.toFixed(1)}%)`, 'Resto de la Población'],
                datasets: [{
                    data: [victimasData.victimas, victimasData.noVictimas],
                    backgroundColor: ['#FFA000', '#0074D9'],
                    borderColor: ['#FFFFFF', '#FFFFFF'],
                    borderWidth: 4,
                    hoverOffset: 8
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                cutout: '70%',
                plugins: {
                    legend: {
                        position: 'bottom',
                        labels: {
                            font: { size: 14 },
                            color: '#003B73',
                            padding: 20
                        }
                    },
                    title: {
                        display: true,
                        text: 'Proporción de la Población Víctima del Conflicto',
                        font: { size: 18, weight: 'bold' },
                        color: '#003B73',
                        padding: {
                            bottom: 20
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    }
                }
            }
        });

        const ctxImpacto = document.getElementById('impactoChart').getContext('2d');
        new Chart(ctxImpacto, {
            type: 'bar',
            data: {
                labels: [
                    wrapLabel('Mejora Calidad de Vida'), 
                    wrapLabel('Atención en Salud Mental'), 
                    wrapLabel('Generación de Empleo Local'), 
                    wrapLabel('Dinamización Económica'),
                    wrapLabel('Símbolo de Reconstrucción')
                ],
                datasets: [{
                    label: 'Impacto Esperado del Proyecto',
                    data: [95, 90, 75, 70, 100],
                    backgroundColor: [
                        '#79BDEE',
                        '#63AEE5',
                        '#4D9FDC',
                        '#3790D3',
                        '#2181CA'
                    ],
                    borderColor: '#FFFFFF',
                    borderWidth: 2,
                    borderRadius: 5
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                indexAxis: 'y',
                scales: {
                    x: {
                        beginAtZero: true,
                        max: 100,
                        ticks: {
                           color: '#FFFFFF'
                        },
                        grid: {
                            color: 'rgba(255, 255, 255, 0.2)'
                        }
                    },
                    y: {
                       ticks: {
                           color: '#FFFFFF',
                           font: {
                               size: 12
                           }
                       },
                       grid: {
                           display: false
                       }
                    }
                },
                plugins: {
                    legend: {
                        display: false
                    },
                    title: {
                        display: true,
                        text: 'Dimensiones del Impacto del Hogar Gerontológico',
                        font: { size: 16, weight: 'bold' },
                        color: '#FFFFFF',
                        padding: {
                            bottom: 20
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>
