# Final_project_PDS4

Назва проекту: Розфарбовування чорно-білого зображення за допомогою нейронної мережі.
Мета
Метою цього проекту є розробка та реалізація нейронної мережі для автоматичного розфарбовування чорно-білих зображень. В проекті показано як нейронна мережа може бути навчена на наборі зображень та використана для колоризації інших чорно-білих зображень.

Опис
Для досягнення поставленої мети побудувано згорткову нейронну мережу, яка здатна розфарбовувати чорно-білі зображення.

Частина 1: Проста версія нейромережі
У цій частині розроблено просту версію нейромережі, яка може розфарбовувати задане чорно-біле зображення. Для цього використовуються згорткові та повнозв'язні шари, архітектура якої підібрана експериментальним шляхом. Ця модель навчається та тренується на одному зображенні, щоб продемонструвати базовий принцип розфарбовування.

Частина 3: Нейромережа з використанням Inception ResNet v2
У цій частині розроблено нейромережу, яка складається з encoder, decoder та fusion layer. Вхідні дані проходять через encoder, де вони перетворюються на багатовимірний простір ознак. Після цього вони проходять через Inception ResNet v2, яка є нейромережею, навченою на великому наборі зображень. На виході моделі отримується розфарбоване зображення.

Використані бібліотеки
Для реалізації проекту використовуються наступні бібліотеки:

numpy: для роботи з масивами та матрицями даних.
os: для роботи з файловою системою, зокрема для завантаження зображень.
matplotlib: для візуалізації та відображення зображень.
Tensorflow: для побудови та тренування нейромережі.
Keras: використовується як високорівневий інтерфейс до Tensorflow для зручного створення моделі та тренування.






