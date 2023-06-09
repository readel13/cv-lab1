## 1. Які різниці між зображеннями при різних порядках каналів?

У зображеннях, кольорова інформація часто подається у вигляді трьох каналів: червоного, зеленого та синього (RGB).
 Різниця у порядку цих каналів може вплинути на вигляд зображення. Наприклад, при переключенні порядку зеленого та
 червоного каналів (GRB замість RGB), зображення може змінитися таким чином, що зелені відтінки стануть більш насиченими,
 а червоні - менш насиченими. Так само, при зміні порядку каналів на BGR, зображення може виглядати інакше, оскільки порядок
 каналів визначає, який колір буде відображатися в якому каналі.
 Отже, в залежності від призначення та конкретної програми або пристрою, може бути важливо визначити правильний
 порядок каналів для відображення кольорової інформації у зображенні.

## 2. Чому так відбувається?

Порядок каналів в кольорових зображеннях визначає, який колір буде відображатися в якому каналі. Це пов'язано з тим, як 
пристрої та програми читають та відображають кольорову інформацію. Наприклад, у зображеннях формату RGB, червоний канал 
містить інформацію про червоні відтінки, зелений - про зелені відтінки, а синій - про сині відтінки. Якщо змінити порядок 
каналів на GRB, то тоді зелений канал буде містити інформацію про червоні відтінки, а червоний - про зелені відтінки. 
Це може вплинути на відображення зображення. Отже, правильний порядок каналів в залежності від програми, пристрою та 
призначення зображення може бути різним, і важливо враховувати це при обробці та відображенні кольорової інформації
 

## 3. Які можуть бути проблеми в додатках комп’ютерного зору, пов’язані з різним порядком колірних каналів?

Неправильний порядок колірних каналів може призвести до різних проблем в додатках комп’ютерного зору.
Ось кілька можливих проблем:

**Пошкодження кольору:** Якщо зображення зберігається або відображається з неправильним порядком кольорів, це може призвести 
до спотворення кольорів на зображенні. Це може зменшити точність розпізнавання об’єктів на зображенні, особливо якщо колір
є важливим фактором для розпізнавання.

**Невідповідність формату зображення:** У деяких випадках формат зображення може вимагати певного порядку кольорів. Наприклад,
формат BMP вимагає, щоб зображення зберігалося в форматі BGR.

**Невдалі перетворення зображень:** У деяких випадках додатки комп’ютерного зору виконують операції над зображеннями, такі як
розмиття, фільтрація або розширення. Якщо при цьому використовується неправильний порядок кольорів, це може призвести до
невдалого результату.