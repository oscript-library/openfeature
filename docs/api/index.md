# Публичный интерфейс библиотеки `openfeature`

## Модули

* [OpenFeature](Модули/OpenFeature.md) - глобальный экземпляр API: провайдер, клиенты, хуки, глобальный контекст
* [OpenFeatureReason](Модули/OpenFeatureReason.md) - причины, по которым получено значение флага
* [OpenFeatureErrorCode](Модули/OpenFeatureErrorCode.md) - коды ошибок оценки флага

## Классы

* [FeatureClient](Классы/FeatureClient.md) - клиент оценки флагов
* [OpenFeatureApi](Классы/OpenFeatureApi.md) - изолированный экземпляр API
* [EvaluationContext](Классы/EvaluationContext.md) - контекст оценки: ключ таргетинга и атрибуты
* [EvaluationDetails](Классы/EvaluationDetails.md) - подробный результат оценки
* [ResolutionDetails](Классы/ResolutionDetails.md) - результат разрешения флага провайдером
* [InMemoryProvider](Классы/InMemoryProvider.md) - провайдер с флагами в памяти
* [JsonFileProvider](Классы/JsonFileProvider.md) - провайдер, читающий флаги из JSON-файла
* [NoopProvider](Классы/NoopProvider.md) - провайдер-заглушка
