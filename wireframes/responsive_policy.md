# Responsive Policy

### Define Mobile View

According to tailwindcss document's responsive design section, `md`'s css `@media` definition is `min-width: 768px`

So, if screen width is below `767px` then application acts as mobile view even if user's device is web browser.

#### Code Style

Example
`w-8 h-4 flex justify-center bg-red-800 md:w-12 md:h-8 md:bg-blue-800`

CSS style applied into both web and mobile
`flex justify-center`

CSS style applied into only mobile
`w-8 h-4 bg-red-800`

CSS style applied into only web
`w-12 h-8 bg-blue-800`
