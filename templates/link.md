{{$week := add (mod (div ((toDate "2006-01-02" "2050-03-13").Sub now).Hours 24) 7) 1}}
{: id="20210117194926-lxv4634"}

## 🕐 创建时间：{{now | date "2006-01-02 15:04"}} {{last (slice (list "星期六" "星期五" "星期四" "星期三" "星期二" "星期一" "星期天") 0 $week )}}
{: id="20210117194739-o26b2sm"}

- {: id="20210117195355-vu2msvl"}
{: id="20210117195354-apri570"}

{: id="20210117202646-zftsztx"}

---

{: id="20210117210830-upmuwg8"}

{: id="20210117210830-9t2553u"}

## 🔗 提及“{{.title}}”的内容
{: id="20210117201946-iesarol"}

!{{SELECT * FROM blocks WHERE content LIKE '%{{.title}}%' and path not LIKE '%{{.title}}%'}}
{: id="20210117192741-ydqeurt"}

{: id="20210117210825-jxrp1os"}

{: id="20210117210825-74q2lw8"}

{: id="20210117210825-kz6syn3"}

{: id="20210117210825-x9b1bsy"}

{: id="20210117210825-s54dvkk"}

{: id="20210117210825-8afl65e"}

{: id="20210117210825-hbktugu"}


{: id="20210117192611-6c17hv1" type="doc"}
