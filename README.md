# GPT-builder

## Описание

GPT-builder - инструмент для создания CSV датасетов с использованием искусственного интеллекта, предназначенный для обучения текстовых моделей. Этот инструмент обеспечивает легкость создания разнообразных текстовых диалогов, которые могут быть использованы для обучения различных ии моделей.

## Пример Работы

Процесс взаимодействия с GPT-builder следующий:

1. Пользователь начинает с команды `/start`, запуская создание датасета.
2. GPT-builder приветствует пользователя и предлагает ввести первый текст для датасета.
3. Пользователь вводит текст, например, "Hello!".
4. GPT-builder предлагает выбрать режим: автоматический или ручной.
   - Автоматический режим позволяет GPT-builder автоматически дополнять ответы бота к введенным запросам.
   - Ручной режим дает пользователю полный контроль над созданием датасета, где он сам вводит запросы и ответы бота.
5. Пользователь выбирает режим, например, "Автоматика".
6. GPT-builder создает CSV файл с первым текстовым запросом и автоматически добавляет ответы бота, создавая датасет для обучения.


*Если GPT-3.5 пишет в блок коде, Попытайтесь сгенерировать заново ответ.*


Процесс повторяется для добавления дополнительных запросов и ответов. Инструкции и предупреждения также предоставляются в случае изменения темы разговора.

## Как использовать?

![тест](https://github.com/C4ainikT/GPT-Builder.Dataset-Custom-Instruction-RUSSION/assets/129612159/924b02e5-e45e-4c30-ae1c-fa7467c3fbf7)





## Зависимости

- Python 3.x
- Дополнительные зависимости указаны в файле `requirements.txt`

## Лицензия

Этот проект распространяется под [лицензией MIT](LICENSE).
