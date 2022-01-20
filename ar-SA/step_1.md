غالبًا ما يكون من المفيد في Scratch تشغيل التعليمات البرمجية في كل مرة يصبح فيها الشرط صحيحًا.

يمكنك القيام بذلك عن طريق وضع `اذا`{: class = "block3control"} داخل التعليمة البرمجية`كرر باستمرار`{: class = "block3control"}. وسوف تحتاج لحدث، على سبيل المثال `عند نقر العلم` {:class="block3events"} أو المقطع البرمجي `عندما اتلقى`{:class="block3events"}.

يمكنك التحقق من الشروط المهمة في اللعبة:

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

أو افحص باستخدام `العمليات`{:class="block3variables"} بقيمة `متغير`{:class="block3operators"}.

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
