# Pavel Nikolaev

## Front-end developer

---

### Contact information

- **Phone:** +79679891035
- **E-mail:** ajambex@ya.ru
- **Telegram:** [@ajambex](https://t.me/ajambex)
- **LinkedIn:** [Pavel Nikolaev](https://linkedin.com/in/pavel-nikolaev-58707a269)

---

### Briefly about myself

I became interested in web interface development when I was a schoolboy. At that time, free hosting narod.ru from Yandex was very popular. I created a home page on it, published information about myself and my interests. I dreamed of making a site with a lot of traffic, so that all my friends would go there and be able to chat. But a few years later, such a site was created by Pavel Durov, and by that time I had only good knowledge of HTML and CSS.

At some point, I became interested in foreign languages, and this interest outweighed everything else for me for many years. I entered the university, studied as a translator of English and German, received a diploma and have been working in my specialty for almost nine years.

However, now I have a feeling that I have achieved maximum results in my profession and now I want to change it. I already have some experience in web development. For example, I created a travel website [aidazanami.ru](https://aidazanami.ru) and have been earning money on it for several years, and sometimes I take orders for website composition on freelance exchanges. In the near future I will improve my skills in front-end development and start a career in this area.

---

### My skills

- HTML
- CSS (+ Sass)
- JavaScript (ES5, ES6+, [Codewars 5 kuy](https://www.codewars.com/users/rsschool_07725fadc07f0dd3))
- Git (+ console), GitHub ([my profile](https://github.com/vspaker))
- VS Code
- Photoshop, Figma

---

### Code exapmle

**Human readable duration format from CODEWARS:** _The task in order to complete this Kata is to write a function which formats a duration, given as a number of seconds, in a human-friendly way. The function must accept a non-negative integer. If it is zero, it just returns "now". Otherwise, the duration is expressed as a combination of years, days, hours, minutes and seconds._

```
function formatDuration (seconds) {
  if (seconds === 0) {
    return `now`;
  }

  const SECONDS_PER_YEAR = 31536000;
  const SECONDS_PER_DAY = 86400;
  const SECONDS_PER_HOUR = 3600;
  const SECONDS_PER_MINUTE = 60;

  const years = Math.floor(seconds / SECONDS_PER_YEAR);
  const days = Math.floor((seconds % SECONDS_PER_YEAR) / SECONDS_PER_DAY);
  const hours = Math.floor((seconds - (years * SECONDS_PER_YEAR) - (days * SECONDS_PER_DAY)) / SECONDS_PER_HOUR);
  const minutes = Math.floor((seconds - (years * SECONDS_PER_YEAR) - (days * SECONDS_PER_DAY) - (hours * SECONDS_PER_HOUR)) / SECONDS_PER_MINUTE);
  const secs = seconds - (years * SECONDS_PER_YEAR) - (days * SECONDS_PER_DAY) - (hours * SECONDS_PER_HOUR) - (minutes * SECONDS_PER_MINUTE);

  const yearComponent = years ? `${years} ${years > 1 ? `years` : `year`}` : ``;
  const dayComponent = days ? `${days} ${days > 1 ? `days` : `day`}` : ``;
  const hourComponent = hours ? `${hours} ${hours > 1 ? `hours` : `hour`}` : ``;
  const minuteComponent = minutes ? `${minutes} ${minutes > 1 ? `minutes` : `minute`}` : ``;
  const secondsComponent = secs ? `${secs} ${secs > 1 ? `seconds` : `second`}` : ``;

  const components = [];
  components.push(yearComponent, dayComponent, hourComponent, minuteComponent, secondsComponent);

  const filteredComponents = components.filter(el => el.length > 1);

  if (filteredComponents.length > 1) {
    for (let i = 0; i < filteredComponents.length; i++) {

      if (i < filteredComponents.length - 2) {
        filteredComponents[i] = `${filteredComponents[i]}` + `, `;
      } else if (i === filteredComponents.length - 1) {
        filteredComponents[i] = ` and ` + `${filteredComponents[i]}`
      }
    }
  } else {
    return filteredComponents.join("");
  }

  return filteredComponents.join("");
}
```

---

### Cources

- **HTML Academy:** [my profile](https://htmlacademy.ru/profile/ajambex)
- **Codewars:** [my profile](https://www.codewars.com/users/rsschool_07725fadc07f0dd3)

---

### Languages

- Russian: _native_
- English: _intermediate_
- German: _basic_
