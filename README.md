Frontend
HTML

CSS/SCSS/LESS

Javascript
- Typescript:
- ES6: 
  1. Multiline string es6: console.log(`Fifteen is ${a + b} andnot ${2 * a + b}.`);
  
Angular
- Data binding
  Component -> View 
  1. Interpolation: {{ value }}
  2. Property binding: [property] = "value"
  3. Attribute binding: [attr.attribute_name] = "value"
  4. Class binding: [class.class_name] = "value"
  5. Style binding: [style.style_name] = "value"
  View -> component
  1. Event biding: (event_name)="nameFunction($event)"
  View -> Component -> View
  1.Two-way binding: -  import FormsModule
                     -  [(ngModel)]="value"
                     -  Need name="name"
- Directive
  1. ngIf
  2. ngFor
  3. ngSwitch
  4. ngClass
  5. ngStyle
- Input - Output
  @Input: - Parent -> child
          - Parent: [key]="value" -> child: @Input() key
  @Output: - Child -> parent
           - Child: @Output('key') fnc = new EventEmitter<typeData>();
                    this.fnc.emit(this.key);
           - Parent: (key) = fnc()
           - () : Khai báo giá trị trả ra ngoài
           - (params).emit(value)
- Pipe
- Template Reference Variables (tham chiếu đến một phần tử Dom hoặc directice trong template)
   Tempalte: #name or ref-name
   Component: @Viewchild('name1') name2: ElementRef
- Lifecycle Hooks
  1. Contructor (not lifecycle)
  2. ngOnInit
  3. ngOnDestroy
  4. ngOnChanges -> ngOnDocheck
  5. ngContent
  6. ngAfterContentInit
  7. ngAfterContentInit
  8. ngAfterView, ngAfterViewCheched
- Service (Dependency Injection)
   
Backend
ASP.NET core/EF core
- Linq


SQL Server
  
