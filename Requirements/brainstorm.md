# Сбор требований через мозговой штурм


## Участники
- Мамедов Рафаэль
- Agent2
- Agent3


## Цель мозгового штурма:
Определение функциональных и нефункциональных требований при разработке VPNSurfer

## Список предложенных требований





### Функциональные требования
1. **Регистрация и авторизация**
   - Пользователь должен иметь возможность зарегистрироваться через бот, используя телефонный номер, электронную почту или через аутентификацию в Telegram.
   - Возможность входа в систему после регистрации.

2. **Оформление подписки**
   - Возможность выбора и оплаты подписки на VPN-сервис (ежемесячная, годовая).
   - Поддержка нескольких методов оплаты (карты, СБП, оплата по QR и т.д.)

3. **Выбор VPN сервера**
   - Возможность выбора сервера из нескольких доступных вариантов (разных стран или регионов).
   - Возможность автоматического подключения к наименее загруженному серверу.

4. **Получение настроек и базы конфигураций:**
   - После успешного выбора сервера пользователь получает инструкции и файлы конфигурации для подключения к VPN.

5. **Управление и мониторинг:**
   - Возможность просмотра текущего статуса подписки.
   - Возможность продления или отмены подписки.
   - Просмотр статистики использования: данные о трафике и времени подключения.

6. **Поддержка пользователей:**
   - Возможность связаться с технической поддержкой через бот.
   - Доступ к базе знаний и FAQ для самостоятельного решения проблем.

7. **Настройка уведомлений:**
   - Уведомления о приближении конца подписки.
   - Уведомления о новых доступных серверах.


### Нефункциональные требования
1. **Производительность:**
   - Бот должен обрабатывать запросы пользователей с минимальными задержками.

2. **Масштабируемость:**
   - Система должна обеспечивать возможность масштабирования для поддержки растущего количества пользователей и запросов.
   - Поддержка облачной инфраструктуры для динамического увеличения ресурсов.

3. **Надежность и доступность:**
   - Высокая доступность сервиса.
   - Надежность хранения пользовательских данных.

4. **Безопасность:**
   - Поддержка шифрования данных при передаче и хранении.
   - Защита от атак типа DDoS.

5. **Интерфейсность:**
   - Возможность взаимодействия через текстовые команды или кнопки интерфейса Telegram.

6. **Логирование и мониторинг:**
   - Ведение логов работы системы для последующего анализа и улучшения.
   - Реализация системы оповещений для мониторинга состояния серверов и бота.

## Результаты после проведения мозгового штурма
- Сформированы функциональные и нефункциональные требования.
- Заявлена цель проекта.

## Дальнейшие действия
- Декомпозиция требований
- Проведение анкетирования и интервью с целью детализации требований
- Формирование ТЗ