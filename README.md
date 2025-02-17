<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ТехноМаркет - Магазин бытовой техники</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <!-- Шапка сайта -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <a class="navbar-brand" href="#">ТехноМаркет</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#main">Главная</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#products">Товары</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#benefits">Преимущества</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Контакты</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Герой-секция -->
    <section id="main" class="py-5 bg-primary text-light">
        <div class="container text-center">
            <h1 class="display-4">Лучшая бытовая техника по выгодным ценам</h1>
            <p class="lead">Огромный выбор холодильников, стиральных машин, плит и другой техники</p>
            <a href="#products" class="btn btn-light btn-lg mt-3">Смотреть каталог</a>
        </div>
    </section>

    <!-- Секция с каруселью акций -->
    <section id="promo" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Акционные предложения</h2>
            <div id="promoCarousel" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="https://img.freepik.com/premium-photo/home-appliance-fridge-cooker-washing-machine-household-equipment-white-color_1190773-1036.jpg?w=1380" alt="Акция">
                    </div>
                    <div class="carousel-item">
                        <img src="https://img.freepik.com/premium-photo/group-home-appliances-near-wall-blue-studio-background_241146-2663.jpg?w=1380" alt="Акция">
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#promoCarousel" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#promoCarousel" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                </button>
            </div>
        </div>
    </section>

    <!-- Секция с товарами -->
    <section id="products" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Популярные товары</h2>
            <div class="row">
                <!-- Холодильник -->
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <img src="https://img.freepik.com/free-photo/refrigerator-surrounded-by-nature-scene_23-2150165603.jpg?t=st=1739767050~exp=1739770650~hmac=84360e93e54d08f35e808a6cd12fffcee54b444d5c3a359d22d5dc8e5d223513&w=740" class="card-img-top" alt="Холодильник">
                        <div class="card-body">
                            <h5 class="card-title">Холодильник Samsung</h5>
                            <p class="card-text">
                                <span class="text-danger h4">59 990 ₽</span>
                                <del class="text-muted">69 990 ₽</del>
                            </p>
                            <button class="btn btn-primary w-100">Купить</button>
                        </div>
                    </div>
                </div>

                <!-- Стиральная машина -->
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <img src="https://img.freepik.com/premium-photo/tech-device-with-nature-background_23-2150470421.jpg?w=740" alt="Стиральная машина">
                        <div class="card-body">
                            <h5 class="card-title">Стиральная машина Bosch</h5>
                            <p class="card-text">
                                <span class="h4">34 490 ₽</span>
                            </p>
                            <button class="btn btn-primary w-100">Купить</button>
                        </div>
                    </div>
                </div>

                <!-- Духовой шкаф -->
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <img src="https://img.freepik.com/free-photo/mom-spending-time-with-her-kid_23-2149495916.jpg?t=st=1739767259~exp=1739770859~hmac=f45ea2a7504dfa4f211902ede6445e2f19d542de667074bc6de49e100e2f8b52&w=900">
                        <div class="card-body">
                            <h5 class="card-title">Духовой шкаф Electrolux</h5>
                            <p class="card-text">
                                <span class="h4">22 790 ₽</span>
                            </p>
                            <button class="btn btn-primary w-100">Купить</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Секция преимуществ -->
    <section id="benefits" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Почему выбирают нас</h2>
            <div class="row text-center">
                <div class="col-md-4 mb-4">
                    <div class="p-3">
                        <h4>Бесплатная доставка</h4>
                        <p>По всей России при заказе от 20 000 ₽</p>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="p-3">
                        <h4>Гарантия 2 года</h4>
                        <p>Официальная гарантия на всю технику</p>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="p-3">
                        <h4>Рассрочка 0%</h4>
                        <p>Возможность оплаты частями без переплат</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Секция контактов -->
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h2>Наши контакты</h2>
                    <p class="mt-4">
                        <strong>Адрес:</strong> г. Самара, ул. Антонова-Овсеенко, 83<br>
                        <strong>Телефон:</strong> +7 (917) 036-36-26<br>
                        <strong>Email:</strong> kirill0063@gmail.com
                    </p>
                    <h4 class="mt-5">Мы в соцсетях:</h4>
                    <div class="social-links">
                        <a href="https://vk.com/areski" class="btn btn-outline-dark me-2">VK</a>
                        <a href="https://telegram.me/AresC404" class="btn btn-outline-dark me-2">Telegram</a>
                    </div>
                </div>
                <div class="col-md-6">
                    <h2>Остались вопросы?</h2>
                    <form class="mt-4">
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Ваше имя">
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Ваш email">
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="4" placeholder="Ваш вопрос"></textarea>
                        </div>
                        <button class="btn btn-primary w-100">Отправить</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Подвал -->
    <footer class="bg-dark text-light py-4">
        <div class="container text-center">
            <p class="mb-0">© 2025 ТехноМаркет. Все права защищены</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
