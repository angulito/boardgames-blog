---
title: "Contacto"
description: "Contacto"
date: 2020-01-27
aliases: ["contact"]
author: "Hugo Authors"
---

{{< rawhtml >}}

<div class="content">
    <p class="mb-2">Para contactarnos, por favor rellena el siguiente formulario.</p>
    <form name=contact action=https://formspree.io/f/xleozkjn method=post>
    <div class="mb-4">
         <input type=text placeholder="Tu nombre" name=name class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required>
    </div>
    <div class="mb-4">
        <input type=text placeholder="Dirección de correo electrónico" name=mail class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required>
    </div>
    <div class="mb-4">
        <input type=text placeholder="Asunto" name=title class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required>
    </div>
    <div class="mb-4">
        <textarea rows=5 cols=30 placeholder="Mensaje" name=message class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required></textarea>
    </div>
    <input type=submit value="Submit" class="w-full button duration-100 py-2 bg-gray-800 text-white cursor-pointer transition-colors hover:bg-gray-600">
    </form>
</div>
{{< /rawhtml >}}
