
# **gScreenshot**

| [ру](https://github.com/Giovanny472/gscreenshot) | [es](https://github.com/Giovanny472/gscreenshot/blob/main/README.es.md) |

Простая программа для скриншотов. Написано на языке go.  
Эта программа основана на библиотеке  [screenshot](https://github.com/kbinani/screenshot). C помощью библиотек: [glfw](https://github.com/go-gl/glfw) и [gl](https://github.com/go-gl/gl) был реализован интерфейс пользователя, который позволяет выбрать область(координаты) на экране.  Эти координаты передаются в качестве параметров в библиотеку [screenshot](https://github.com/kbinani/screenshot), чтобы сделать снимок экрана. После получения изображения выбранной области экрана используется библиотека [clipboard](https://github.com/golang-design/clipboard) для передачи изображения в буфер обмена. Таким образом можно получить изображение скриншота простым нажатием ctrl+v.

![gscreenshot](/asset/img/gscreenshot.png)

## Библиотеки использованы
+  [screenshot](https://github.com/kbinani/screenshot)
+  [glfw](https://github.com/go-gl/glfw)
+  [gl](https://github.com/go-gl/gl)
+  [clipboard](https://github.com/golang-design/clipboard) 

https://github.com/Giovanny472/gscreenshot/assets/43882462/cdc30927-4055-4a4d-b065-bf576c4526aa

## Установка программы
Для установки **gScreenshot** можно использовать [gScreenshot_setup.exe](https://github.com/Giovanny472/gscreenshot/releases/tag/v0.1). С помощью ctrl+alt+s можно открыть программу.
