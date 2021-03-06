# Keep Network 101

Keep Network - это решение для обеспечения конфиденциальности, в котором «хранятся» распределенные небольшие объемы данных, например, приватный ключ. Random Beacon и t-ECDSA Keeps - это основная технология сети.

## Что такое Keep?
Keep - это до 1 МБ зашифрованного хранилища, которое распределяется между одним или несколькими провайдерами или участниками. Провайдер Keep - это один экономический субъект в Keep Network; у него есть доля и он может участвовать, как подписант, в подписывающей группе

KEEP - основной токен сети Keep Network. Все приложения в сети построены или будут построены на нем.

Keep Network основывается на надежном источнике случайности для процесса формирования подписывающих групп. Отбор подписантов происходит случайным образом. Этот надежный источник случайности - BLS Threshold Relay, также называемый Random Beacon.

## Что такое Random Beacon?
В основе решения Keep лежит возможность хранить в тайне небольшие объемы данных (например, приватный ключ). Вот почему так важна истинная случайность. Все стороны должны будут вступить в сговор, чтобы узнать, над чем работает пользователь, и сговор становится почти невозможным, когда выбор участников действительно случайный.
Random Beacon - это способ создания, поддающейся проверке, случайности, устойчивой к злоумышленникам как в сети, так и в цепочке Ethereum. Он используется для определения членов для подписывающих групп.

> Прочесть больше о Random Beacon можно в технической документации.

Никто не знает, кем будут подписанты, включая самих подписантов, до того момента, пока они не будут выбраны с помощью Random Beacon. Это гарантирует, что подписанты не смогут вступить в сговор с целью кражи средств или атак на сеть, и именно поэтому так важна истинная случайность, предоставляемая маяком.

Ключевым способом обеспечения надежности tBTC, первого приложения созданного на основе Keep Network, является устранение риска контрагента. Он использует систему групп подписантов, которая позволяет tBTC обрабатывать транзакции без доверенного посредника. Поэтому выбор подписывающей стороны имеет важное значение для надлежащего функционирования tBTC и создания хранилищ t-ECDSA.

## Что такое t-ECDSA Keeps?
t-ECDSA keep - это технология, лежащая в основе tBTC, первого приложения, построенного на Keep Network.

> Прочесть больше о tBTC можно в технической документации.

Реализованный с помощью sMPC, t-ECDSA keep позволяет контрактам обмениваться данными между цепочками путем подписания транзакций с рядом географически распределенных лиц (подписантов). T-ECDSA обеспечивает безопасность транзакций с помощью нескольких отдельных приватных ключей, независимо хранимых несколькими подписантами.

Децентрализованная подпись выполняется с помощью sMPC для вычисления общих приватных ключей без их раскрытия. Ответственность за подписи разделена, и требуется определенное количество участников для создания подписи с использованием своих ключей.

### Хотите узнать о планах по созданию других кросс-чейн токенов? 
Пока нет твердых планов построить мост к другим сетям. Тем не менее, Cross-Chain Group вела переговоры с такими сетями, как Cosmos, Zcash и Polkadot, по поводу этого.

## KEEP: Keep Network токен
Баланс токенов KEEP необходим для того, чтобы стать участником Keep Network. Участники имеют право получать вознаграждения, выполняя работу на платформе. Это ключевой стимул, который стимулирует конструктивное поведение, способствует эффективности и доверию, а также способствует принятию и росту Keep Network.

KEEP - это рабочий токен, владение которым дает право выполнять ключевые функции в сети. Держатели токенов должны делегировать минимальную сумму KEEP в качестве обеспечения, чтобы иметь право на участие.

Объем работы, для которой выбирается делегат, будет пропорционален количеству делегированных KEEP. Например, человек, делегирующий 1000 KEEP, со временем может ожидать, что его будут отбирать для работы в десять раз чаще, чем человека, делегирующего 100 KEEP, и получать вознаграждение пропорционально работе, которую он успешно выполняет.

## Награды и сокращения
Преимущество токенов KEEP для держателей зависит от суммы делегированной доли. Идея в том, что те, у кого больше доля, получат больше награды.

Сокращение в системах Keep и tBTC не предназначено для наказания, а скорее предназначено для защиты безопасности сети от злонамеренного поведения.
Перейдите к следующему разделу, чтобы узнать больше об особенностях наград и сокращений.

`Sourced from Keep Team's official documentation.`[Source](https://keep-network.gitbook.io/staking-documentation/)
`Translator: tony__s_h`
