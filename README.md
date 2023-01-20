## C++ Console Encryption  Project.

### Описание

AES е един от най-използвани алгоритми за криптиране, който използва 128-битов ключ. Взема съобщение от избрат файл и го криптира. Има 10 кръга на криптиране. Всеки кръг съобщението се използва с XOR с ключа.
AES осигурява сигурно и практически неразбиваемо криптиране.
Процесът на декриптиране използва стъпките на обратно, за да декриптира съобщение.

## По време на работа

Има две програми: за криптиране и за декриптиране.
За криптиранет: в текстовия файл в проекта въвеждаме съобщение, въвеждаме 16 символен ключ и стартираме програмата. Тя връща в message.aes криптираното съобщение.
За декриптиране: Имаме текстов файл, в който се въвежда въпрсния 16-символн ключ и стартираме програмета. Тя автоматично взима криптираното съобщение и го декриптира като го изписва в конзолата и го запазва в текстов файл.

## Заключение 

Това е един от най-сигурните и най-бързите криптиращи методи, който се използва в модерния свят.Има 256^16 комбинации за ключ. Изчислява се, че на най-бързите компютри за момента би им отнело дестки години да декриптират най-просто съобщение без ключ.