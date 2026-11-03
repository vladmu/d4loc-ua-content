# Disclaimer / Відмова від відповідальності

This document is given in full in two languages: English first, Ukrainian second. The English text is the legally binding one; the Ukrainian text is a translation provided for convenience.

Цей документ наведено повністю двома мовами: спершу англійською, потім українською мовою. Юридичну силу має англійський текст; український текст є перекладом для зручності.

---

# English

## Summary

- The project is unofficial. By using the application, the translation or the voice-over you agree that **any consequences (loss or damage of game files, saves and settings; crashes of the game, the operating system, other programs or hardware; account bans; breaches of the publisher's or platform's rules) are entirely your own responsibility.** The author and contributors accept no liability for any damage.
- The application and the translation are provided **"as is"**, without warranty of any kind, including that they will work with your version of the game.
- Back up the game folder and your saves yourself before installing, especially after a game update.
- The author is not liable for loss of game files, saves, progress or settings, for crashes of the game, the system or other programs, or for any damage to the system or hardware (including overheating or load on a graphics card while voice-over is synthesized).
- The installer **changes files in the game folder**. It adds its own Ukrainian-language files and **one line** to every existing language file (`loca_*_texts.csv`), following the pattern `_languageName_uk,<name of the Ukrainian language>,,`, where the name is written in the language of that file (`Ukrainian` in the English file, `украинский (Ukrainian)` in the Russian one), so that the Ukrainian language appears in the language menu. This is a limitation we have not found a way around; nothing else in the existing files is changed (see the README, section "Що змінюється в оригінальних файлах гри"). Before that, every such file is copied next to the original as `D4Loc_<name>.bak`. Uninstalling restores these files to the original.
- The project is not affiliated with, or endorsed by, Realmforge Studios, Kalypso Media or any other rights holder of Dungeons 4. Game names and materials belong to their owners. No game files are distributed in the repository.
- The translation was produced with the help of AI (Gemma 3, Claude) and the voice-over is synthesized (Holos TTS): errors in text, stress and intonation are possible.
- Whether the use of modifications is allowed by the rules of the publisher, the platform or the online mode is for you to check.

## Availability, removal and voices

- The project may be changed or taken down at the reasonable request of the game's rights holders or other persons. The author does not guarantee continuous availability of the repository, releases, translation or voice-over. Keep your own copies.
- The Ukrainian text was created on the basis of the game's text; the English original is not included in the repository.
- The voice-over was created with the Holos TTS synthesizer using its ready-made voices (presets). The origin of these voices and the rights to them are unknown to the author of the project. If a claim arises, the voices will be replaced.

## Standard wording (CC BY-SA 4.0, section 5)

This is the standard wording from the Creative Commons Attribution-ShareAlike 4.0 International Public License, under which the translation and the voice-over in this repository are distributed (full text in `LICENSE`). A similar provision (sections 15 and 16) is in the GNU GPL v3, which applies to the code of the application (repository `d4loc-ua-tool`).

### Disclaimer of Warranties and Limitation of Liability

a. UNLESS OTHERWISE SEPARATELY UNDERTAKEN BY THE LICENSOR, TO THE EXTENT POSSIBLE, THE LICENSOR OFFERS THE LICENSED MATERIAL AS-IS AND AS-AVAILABLE, AND MAKES NO REPRESENTATIONS OR WARRANTIES OF ANY KIND CONCERNING THE LICENSED MATERIAL, WHETHER EXPRESS, IMPLIED, STATUTORY, OR OTHER. THIS INCLUDES, WITHOUT LIMITATION, WARRANTIES OF TITLE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, ABSENCE OF LATENT OR OTHER DEFECTS, ACCURACY, OR THE PRESENCE OR ABSENCE OF ERRORS, WHETHER OR NOT KNOWN OR DISCOVERABLE. WHERE DISCLAIMERS OF WARRANTIES ARE NOT ALLOWED IN FULL OR IN PART, THIS DISCLAIMER MAY NOT APPLY TO YOU.

b. TO THE EXTENT POSSIBLE, IN NO EVENT WILL THE LICENSOR BE LIABLE TO YOU ON ANY LEGAL THEORY (INCLUDING, WITHOUT LIMITATION, NEGLIGENCE) OR OTHERWISE FOR ANY DIRECT, SPECIAL, INDIRECT, INCIDENTAL, CONSEQUENTIAL, PUNITIVE, EXEMPLARY, OR OTHER LOSSES, COSTS, EXPENSES, OR DAMAGES ARISING OUT OF THIS PUBLIC LICENSE OR USE OF THE LICENSED MATERIAL, EVEN IF THE LICENSOR HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH LOSSES, COSTS, EXPENSES, OR DAMAGES. WHERE A LIMITATION OF LIABILITY IS NOT ALLOWED IN FULL OR IN PART, THIS LIMITATION MAY NOT APPLY TO YOU.

c. THE DISCLAIMER OF WARRANTIES AND LIMITATION OF LIABILITY PROVIDED ABOVE SHALL BE INTERPRETED IN A MANNER THAT, TO THE EXTENT POSSIBLE, MOST CLOSELY APPROXIMATES AN ABSOLUTE DISCLAIMER AND WAIVER OF ALL LIABILITY.

## Not legal advice

This is not legal advice. The law of your country may limit disclaimers of liability; in that case the disclaimer applies to the extent permitted by law.

---

# Українською мовою

## Коротко

- Проєкт неофіційний. Використовуючи застосунок, переклад чи озвучення, ви погоджуєтесь, що **будь-які наслідки (втрата або пошкодження файлів гри, збережень і налаштувань; збої гри, операційної системи, інших програм чи апаратного забезпечення; блокування облікового запису; порушення правил видавця чи платформи) цілком лежать на вашій відповідальності.** Автор і учасники не несуть відповідальності за жодні збитки.
- Застосунок і переклад надаються **«як є»** («as is»), без гарантій будь-якого роду, зокрема без гарантії працездатності з вашою версією гри.
- Перед установкою зробіть власну копію теки гри й збережень, особливо після оновлення гри.
- Автор не відповідає за втрату файлів гри, збережень, прогресу чи налаштувань, за збої гри, системи чи інших програм, а також за будь-які пошкодження системи чи обладнання (включно з перегрівом чи навантаженням відеокарти під час синтезу озвучення).
- Інсталятор **змінює файли в теці гри**: додає власні файли української мови та **один рядок** у кожен наявний мовний файл (`loca_*_texts.csv`) за шаблоном `_languageName_uk,<назва української мови>,,`, де назва записана мовою цього файлу (в англійському `Ukrainian`, в російському `украинский (Ukrainian)`), щоб українська мова з'явилась у меню мов. Це обмеження, яке ми не знайшли як обійти; нічого іншого в наявних файлах не змінюється (див. README, розділ «Що змінюється в оригінальних файлах гри»). Перед цим кожен такий файл копіюється поряд як `D4Loc_<ім'я>.bak`. Видалення української мови повертає ці файли до оригіналу.
- Проєкт не пов'язаний із Realmforge Studios, Kalypso Media та іншими правовласниками Dungeons 4 і не схвалений ними. Назви та матеріали гри належать їхнім власникам. Файли гри в репозиторії не поширюються.
- Переклад створено з участю ШІ (Gemma 3, Claude), озвучення синтезовано (Holos TTS): можливі помилки тексту, наголосів, інтонацій.
- Чи дозволяє використання модифікацій правила видавця, платформи чи онлайн-режиму, ви перевіряєте самостійно.

## Доступність, видалення і голоси

- Проєкт може бути змінений або знятий з публікації за обґрунтованою вимогою правовласників гри чи інших осіб. Автор не гарантує безперервної доступності репозиторію, релізів, перекладу чи озвучення. Радимо зберігати власні копії.
- Український текст створено на основі тексту гри; англійського оригіналу в репозиторії немає.
- Озвучення створено синтезатором Holos TTS на його готових голосах (пресетах). Походження цих голосів і права на них автору проєкту невідомі. Якщо виникне претензія, голоси буде замінено.

## Стандартне формулювання (CC BY-SA 4.0, розділ 5): переклад

Нижче переклад стандартного формулювання з ліцензії Creative Commons Attribution-ShareAlike 4.0 International, під якою в цьому репозиторії поширюються переклад та озвучення (повний текст у `LICENSE`). Подібне положення (розділи 15 і 16) є і в GNU GPL v3, що діє для коду застосунку (репозиторій `d4loc-ua-tool`). Переклад неофіційний; у разі розбіжностей чинний англійський текст вище.

### Відмова від гарантій і обмеження відповідальності

a. Якщо Ліцензіар окремо не зобов'язався інакше, у межах можливого Ліцензіар пропонує Ліцензований матеріал «як є» та «як доступний» і не робить жодних заяв чи гарантій будь-якого роду щодо Ліцензованого матеріалу, явних, неявних, встановлених законом чи інших. Це включає, зокрема, гарантії права власності, товарної придатності, придатності для певної мети, ненарушення прав, відсутності прихованих чи інших дефектів, точності, наявності чи відсутності помилок, відомих чи виявних. Якщо відмова від гарантій повністю або частково не допускається, ця відмова може не поширюватися на вас.

b. У межах можливого Ліцензіар ні за яких обставин не відповідатиме перед вами за жодною правовою підставою (зокрема через недбалість) чи інакше за будь-які прямі, особливі, непрямі, випадкові, побічні, штрафні, показові чи інші втрати, витрати чи збитки, що виникли внаслідок цієї публічної ліцензії чи використання Ліцензованого матеріалу, навіть якщо Ліцензіара було попереджено про можливість таких втрат, витрат чи збитків. Якщо обмеження відповідальності повністю або частково не допускається, це обмеження може не поширюватися на вас.

c. Наведену вище відмову від гарантій та обмеження відповідальності слід тлумачити так, щоб у межах можливого вони якнайближче відповідали абсолютній відмові від гарантій і зреченню будь-якої відповідальності.

## Не юридична консультація

Це не юридична консультація. Законодавство вашої країни може обмежувати відмову від відповідальності; у такому разі вона діє в межах, дозволених законом.
