```html
  <ngx-extended-pdf-viewer
    *ngIf="showPdfViewer"
    [src]="'...'"
    [pageViewMode]="'infinite-scroll'"
    [useBrowserLocale]="true"
    [textLayer]="showWidgets"
    (pagesLoaded)="onPagesLoaded($event)"
    [showHandToolButton]="showWidgets"
    [showToolbar]="showWidgets"
    [sidebarVisible]="showWidgets"
  >
  </ngx-extended-pdf-viewer>

```