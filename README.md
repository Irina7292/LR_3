# LR_3

Якщо отримуємо помилку авторизації – наприклад, 403 

$ git push -u origin master
remote: Permission to Irina7292/LR_3.git denied to alina-tushych.
fatal: unable to access 'https://github.com/Irina7292/LR_3.git/': The requested URL returned error: 403

Можна видалити старі ключі авторизації через панель керування:

Панель управления –> Учетные записи пользователей –> Администрирование учетных записей –> Учетные данные Windows –> Общие учетные данные –> git:https://github.com –> Удалить 

control panel > user accounts > credential manager > Windows credentials > Generic credentials
Next, remove the Github keys.

