<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Сенсационное открытие: почему Дианы - лучшие жены</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;500&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            scroll-behavior: smooth;
        }
        
        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
        }
        
        .hero {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
        }
        
        .fade-in {
            animation: fadeIn 1.5s ease-in-out;
        }
        
        .slide-up {
            animation: slideUp 1s ease-out;
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes slideUp {
            from { 
                opacity: 0;
                transform: translateY(50px);
            }
            to { 
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .stat-card {
            transition: all 0.3s ease;
        }
        
        .stat-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .timeline-item {
            position: relative;
            padding-left: 3rem;
        }
        
        .timeline-item:before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            width: 2px;
            height: 100%;
            background: #3b82f6;
        }
        
        .timeline-dot {
            position: absolute;
            left: -0.5rem;
            top: 0;
            width: 1.5rem;
            height: 1.5rem;
            border-radius: 50%;
            background: #3b82f6;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
        }
        
        .parallax {
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- Навигация -->
    <nav class="bg-white shadow-lg sticky top-0 z-50 fade-in">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <div class="flex items-center space-x-4">
                    <div class="w-10 h-10 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold">D</div>
                    <span class="font-semibold text-lg">Diana Research</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#research" class="hover:text-blue-500 transition">Исследование</a>
                    <a href="#facts" class="hover:text-blue-500 transition">Факты</a>
                    <a href="#methodology" class="hover:text-blue-500 transition">Методология</a>
                    <a href="#conclusion" class="hover:text-blue-500 transition">Выводы</a>
                </div>
                <button class="md:hidden">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Герой -->
    <section class="hero min-h-screen flex items-center justify-center py-20 fade-in">
        <div class="max-w-6xl mx-auto px-6 text-center">
            <div class="bg-white bg-opacity-80 backdrop-blur-sm rounded-xl p-8 md:p-12 shadow-xl slide-up">
                <span class="inline-block px-4 py-1 bg-blue-100 text-blue-600 rounded-full mb-4">Новое исследование</span>
                <h1 class="text-4xl md:text-6xl font-bold mb-6">Британские ученые доказали: <span class="text-blue-600">Дианы</span> — лучшие жены</h1>
                <p class="text-xl md:text-2xl mb-8">Особенно те, кто во вторник опаздывает на электричку и приезжает с работы поздно</p>
                <div class="flex flex-col sm:flex-row justify-center gap-4">
                    <a href="#research" class="px-8 py-3 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition transform hover:scale-105 shadow-lg pulse">Узнать больше</a>
                    <a href="#conclusion" class="px-8 py-3 border-2 border-blue-600 text-blue-600 rounded-full hover:bg-blue-50 transition transform hover:scale-105">Основные выводы</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Основной контент -->
    <main class="max-w-6xl mx-auto px-6 py-20">
        <!-- Раздел исследования -->
        <section id="research" class="mb-32 scroll-mt-20">
            <div class="text-center mb-16 slide-up">
                <span class="inline-block px-4 py-1 bg-blue-100 text-blue-600 rounded-full mb-4">Сенсация</span>
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Революционное открытие в области семейных отношений</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">После 5 лет исследований с участием 10,000 пар британские ученые пришли к неожиданному выводу</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12 items-center mb-16">
                <div class="slide-up" style="animation-delay: 0.2s;">
                    <img src="https://images.unsplash.com/photo-1580489944761-15a05d5d4b9f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Счастливая пара" class="rounded-xl shadow-2xl w-full h-auto">
                </div>
                <div class="slide-up" style="animation-delay: 0.4s;">
                    <h3 class="text-2xl font-bold mb-4">Почему именно Дианы?</h3>
                    <p class="text-lg mb-6">Исследование показало, что женщины с именем Диана обладают уникальным сочетанием качеств, которые делают их идеальными партнерами. Особенно это проявляется у тех, кто регулярно опаздывает на электричку по вторникам.</p>
                    <ul class="space-y-3 mb-6">
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>На 37% более терпеливы в семейных спорах</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>На 42% чаще проявляют инициативу в решении бытовых вопросов</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>На 28% реже критикуют партнера за мелкие недостатки</span>
                        </li>
                    </ul>
                    <div class="bg-blue-50 border-l-4 border-blue-500 p-4 rounded-r">
                        <p class="italic">"Мы были поражены, обнаружив такую четкую корреляцию между именем, графиком опозданий и качеством семейных отношений"</p>
                        <p class="font-semibold mt-2">— Доктор Эмма Уотсон, руководитель исследования</p>
                    </div>
                </div>
            </div>
            
            <div class="bg-white rounded-xl shadow-xl p-8 md:p-12 slide-up" style="animation-delay: 0.6s;">
                <h3 class="text-2xl font-bold mb-6 text-center">Ключевой фактор: опоздания на электричку по вторникам</h3>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="stat-card bg-white p-6 rounded-lg border border-gray-100 shadow-md">
                        <div class="text-blue-500 text-4xl mb-4">
                            <i class="fas fa-train"></i>
                        </div>
                        <h4 class="font-bold text-xl mb-2">Регулярные опоздания</h4>
                        <p class="text-gray-600">Дианы, опаздывающие на электричку по вторникам, развивают стрессоустойчивость, которая помогает в семейной жизни</p>
                    </div>
                    <div class="stat-card bg-white p-6 rounded-lg border border-gray-100 shadow-md">
                        <div class="text-blue-500 text-4xl mb-4">
                            <i class="fas fa-clock"></i>
                        </div>
                        <h4 class="font-bold text-xl mb-2">Поздний приход с работы</h4>
                        <p class="text-gray-600">Этот фактор коррелирует с высокой рабочей нагрузкой, что развивает многозадачность и организованность</p>
                    </div>
                    <div class="stat-card bg-white p-6 rounded-lg border border-gray-100 shadow-md">
                        <div class="text-blue-500 text-4xl mb-4">
                            <i class="fas fa-heart"></i>
                        </div>
                        <h4 class="font-bold text-xl mb-2">Эмоциональный интеллект</h4>
                        <p class="text-gray-600">Постоянные стрессовые ситуации на транспорте развивают эмпатию и понимание к партнеру</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Раздел фактов -->
        <section id="facts" class="mb-32 scroll-mt-20">
            <div class="text-center mb-16">
                <span class="inline-block px-4 py-1 bg-blue-100 text-blue-600 rounded-full mb-4">Факты</span>
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Удивительные статистические данные</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Результаты исследования, которые заставят вас задуматься</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 mb-16">
                <div class="bg-white p-8 rounded-xl shadow-md text-center slide-up" style="animation-delay: 0.2s;">
                    <div class="text-5xl font-bold text-blue-600 mb-2">87%</div>
                    <p class="text-gray-600">Диан с таким графиком оценивают свои отношения как "очень счастливые"</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md text-center slide-up" style="animation-delay: 0.4s;">
                    <div class="text-5xl font-bold text-blue-600 mb-2">3.5x</div>
                    <p class="text-gray-600">Чаще занимаются совместными хобби по сравнению с другими парами</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md text-center slide-up" style="animation-delay: 0.6s;">
                    <div class="text-5xl font-bold text-blue-600 mb-2">62%</div>
                    <p class="text-gray-600">Их партнеры отмечают улучшение качества жизни после брака</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md text-center slide-up" style="animation-delay: 0.8s;">
                    <div class="text-5xl font-bold text-blue-600 mb-2">91%</div>
                    <p class="text-gray-600">Реже разводятся в первые 10 лет брака по сравнению со средним показателем</p>
                </div>
            </div>
            
            <div class="bg-blue-50 rounded-xl p-8 md:p-12 slide-up" style="animation-delay: 1s;">
                <h3 class="text-2xl font-bold mb-6">История одной Дианы</h3>
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div>
                        <p class="mb-4">"Каждый вторник я опаздываю на электричку из-за утренних совещаний. Вначале это раздражало и моего мужа, и меня, но со временем мы научились ценить эти моменты."</p>
                        <p class="mb-4">"Теперь по вторникам он готовит ужин, а я приезжаю позже. Это стало нашим особым ритуалом, который укрепил наши отношения."</p>
                        <p class="font-semibold">— Диана К., участница исследования, замужем 7 лет</p>
                    </div>
                    <div class="flex justify-center">
                        <div class="w-48 h-48 bg-blue-100 rounded-full flex items-center justify-center overflow-hidden border-4 border-white shadow-xl">
                            <i class="fas fa-user text-6xl text-blue-500"></i>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Раздел методологии -->
        <section id="methodology" class="mb-32 scroll-mt-20">
            <div class="text-center mb-16">
                <span class="inline-block px-4 py-1 bg-blue-100 text-blue-600 rounded-full mb-4">Методология</span>
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Как проводилось исследование</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Научный подход к изучению феномена Диан</p>
            </div>
            
            <div class="max-w-3xl mx-auto">
                <div class="space-y-8 relative">
                    <div class="timeline-item slide-up" style="animation-delay: 0.2s;">
                        <div class="timeline-dot">
                            <i class="fas fa-search"></i>
                        </div>
                        <div class="bg-white p-6 rounded-lg shadow-md">
                            <h3 class="font-bold text-xl mb-2">Фаза 1: Отбор участников</h3>
                            <p class="text-gray-600">Были отобраны 10,000 пар из разных социальных групп, включая 1,200 женщин по имени Диана. Особое внимание уделялось их транспортным привычкам.</p>
                        </div>
                    </div>
                    
                    <div class="timeline-item slide-up" style="animation-delay: 0.4s;">
                        <div class="timeline-dot">
                            <i class="fas fa-clipboard-check"></i>
                        </div>
                        <div class="bg-white p-6 rounded-lg shadow-md">
                            <h3 class="font-bold text-xl mb-2">Фаза 2: Сбор данных</h3>
                            <p class="text-gray-600">В течение 3 лет собирались данные о качестве отношений, частоте конфликтов, уровне удовлетворенности браком и транспортных привычках.</p>
                        </div>
                    </div>
                    
                    <div class="timeline-item slide-up" style="animation-delay: 0.6s;">
                        <div class="timeline-dot">
                            <i class="fas fa-chart-line"></i>
                        </div>
                        <div class="bg-white p-6 rounded-lg shadow-md">
                            <h3 class="font-bold text-xl mb-2">Фаза 3: Анализ</h3>
                            <p class="text-gray-600">Использовались методы машинного обучения и многомерного статистического анализа для выявления скрытых закономерностей.</p>
                        </div>
                    </div>
                    
                    <div class="timeline-item slide-up" style="animation-delay: 0.8s;">
                        <div class="timeline-dot">
                            <i class="fas fa-check-double"></i>
                        </div>
                        <div class="bg-white p-6 rounded-lg shadow-md">
                            <h3 class="font-bold text-xl mb-2">Фаза 4: Верификация</h3>
                            <p class="text-gray-600">Результаты были проверены независимыми экспертами и воспроизведены на дополнительной выборке из 2,000 пар.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Параллакс раздел -->
        <section class="parallax mb-32 py-32 bg-gray-800 text-white bg-opacity-90" style="background-image: url('https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');">
            <div class="max-w-3xl mx-auto px-6 text-center slide-up">
                <h2 class="text-3xl md:text-4xl font-bold mb-6">Городской ритм формирует идеальных партнеров</h2>
                <p class="text-xl mb-8">Исследование показало, что стресс от опозданий на общественный транспорт развивает качества, критически важные для успешных отношений</p>
                <a href="#conclusion" class="inline-block px-8 py-3 bg-white text-blue-600 rounded-full hover:bg-gray-100 transition transform hover:scale-105 shadow-lg">Узнать выводы</a>
            </div>
        </section>

        <!-- Раздел выводов -->
        <section id="conclusion" class="scroll-mt-20">
            <div class="text-center mb-16">
                <span class="inline-block px-4 py-1 bg-blue-100 text-blue-600 rounded-full mb-4">Выводы</span>
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Основные результаты исследования</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Что это значит для современного общества</p>
            </div>
            
            <div class="bg-white rounded-xl shadow-xl overflow-hidden slide-up">
                <div class="grid md:grid-cols-2">
                    <div class="p-8 md:p-12">
                        <h3 class="text-2xl font-bold mb-6">Почему это важно?</h3>
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <div class="bg-blue-100 text-blue-600 rounded-full w-8 h-8 flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-check"></i>
                                </div>
                                <p>Открытие меняет представление о факторах успешного брака</p>
                            </li>
                            <li class="flex items-start">
                                <div class="bg-blue-100 text-blue-600 rounded-full w-8 h-8 flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-check"></i>
                                </div>
                                <p>Показывает важность стрессовых ситуаций для развития личности</p>
                            </li>
                            <li class="flex items-start">
                                <div class="bg-blue-100 text-blue-600 rounded-full w-8 h-8 flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-check"></i>
                                </div>
                                <p>Дает новое понимание влияния городского ритма на семейную жизнь</p>
                            </li>
                        </ul>
                        <div class="bg-blue-50 p-6 rounded-lg">
                            <p class="font-semibold mb-2">Рекомендации исследователей:</p>
                            <p>Если вы встречаетесь с Дианой, которая регулярно опаздывает на электричку по вторникам — не спешите критиковать ее за это. Возможно, именно эти качества делают ее идеальной партнершей.</p>
                        </div>
                    </div>
                    <div class="bg-blue-600 text-white p-8 md:p-12 flex flex-col justify-center">
                        <h3 class="text-2xl font-bold mb-6">Ключевые выводы</h3>
                        <div class="space-y-6">
                            <div>
                                <h4 class="font-bold text-lg mb-2">Имя имеет значение</h4>
                                <p>Женщины по имени Диана статистически демонстрируют более высокие показатели в качестве партнера.</p>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-2">График опозданий</h4>
                                <p>Регулярные опоздания на электричку по вторникам коррелируют с развитием качеств, важных для отношений.</p>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-2">Поздний приход</h4>
                                <p>Приезжающие с работы позже проявляют большую заботу о партнере в выходные дни.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Футер -->
    <footer class="bg-gray-900 text-white py-16 mt-32">
        <div class="max-w-6xl mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-12 mb-12">
                <div>
                    <div class="w-12 h-12 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold text-xl mb-4">D</div>
                    <p class="mb-4">Исследовательский центр Diana Research уже 15 лет изучает факторы успешных семейных отношений.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-facebook"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-linkedin"></i></a>
                    </div>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-4">Исследование</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Методология</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Участники</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Результаты</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Публикации</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-4">Ресурсы</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Блог</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">FAQ</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Поддержка</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Контакты</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-4">Подписаться</h3>
                    <p class="mb-4 text-gray-400">Получайте последние новости о наших исследованиях</p>
                    <div class="flex">
                        <input type="email" placeholder="Ваш email" class="px-4 py-2 rounded-l focus:outline-none text-gray-800 w-full">
                        <button class="bg-blue-600 px-4 py-2 rounded-r hover:bg-blue-700 transition"><i class="fas fa-paper-plane"></i></button>
                    </div>
                </div>
            </div>
            <div class="pt-8 border-t border-gray-800 text-center text-gray-400">
                <p>© 2023 Diana Research. Все права защищены. Любое использование материалов только с разрешения.</p>
            </div>
        </div>
    </footer>

    <script>
        // Плавная прокрутка для якорных ссылок
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Анимация при скролле
        const observerOptions = {
            threshold: 0.1
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animate-fadeIn');
                }
            });
        }, observerOptions);
        
        document.querySelectorAll('.slide-up').forEach(element => {
            observer.observe(element);
        });
    </script>
</body>
</html>
