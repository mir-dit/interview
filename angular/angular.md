1. Что такое pipe и как он работает? pure pipe?
2. Что такое injection token? multi?
3. Какие хуки жизненного цикла есть в angular? В чем отличие NgOnInit от конструктора?
4. В чем разница компонента от директивы?
5. Структурные директивы?
   1. Как отслеживает элементы в ngFor? Что будет, если удалить элемент из середины массива? Как переопределить индексацию?
   2. Как работает ngIf?
6. Ng-container, ng-template, ng-content.
7. Какие есть декораторы?(Input, Output...) Как сделать inject в конструкторе опциональным?(@Optional)
8. Писал ли свой декоратор?
9. Как передаются данные между компонентами в приложениях Angular? (Service, EventEmitter)
10. Dependency Injection, сервисы, provideIn: root, есть ли ngOnDestroy у сервиса?
11. Что такое AOT-компиляция? Какие преимущества AOT-компиляция?
12. NgZone, ChangeDetection компонентов(Default, onPush).
    1. Как срабатывает ререндер в дереве компонентов?
    2. Когда ререндерится OnPush компонент?
    3. Как вызвать ререндер самому? (change detection ref)
    4. runOutsideAngular?
13. Rxjs. Как Angular использует rxjs?
    1. Чем отличаются горячие от холодных потоков?
    2. Что такое Observable?
    3. Чем отличается Observable от Subject?
    4. Чем отличает оператор map от switchMap?
    5. Как в rxjs дождаться выполнение нескольких потоков? (forkJoin, combineLatest)
    6. Как в rxjs выполнять действие на emit из любого потока? (merge)
    7. Отличие merge от concat?
    8. Что будет, если подписываться в нескольких разных местах на поток с запросом к серверу?
    9. Как закешировать последнее значение в потоке?
    10. Behaviour, Reply, async subjects? В чем отличие, в чем особенности?
    11. Утечка памяти после subscribe? Как избежать?