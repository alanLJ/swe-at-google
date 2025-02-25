# 偏见是默认值
当工程师不关注不同国籍、种族、种族、性别、年龄、社会经济地位、能力和信仰体系的用户时，即使是最有才华的员工也会不经意间让他们的用户失望。 这种失败通常是无意的； 所有人都有一定的偏见，社会科学家在过去几十年中已经认识到，大多数人都表现出无意识的偏见，强化和传播现有的刻板印象。 无意识的偏见是阴险的，通常比有意的排斥行为更难缓解。 即使我们想做正确的事，我们也可能无法认识到自己的偏见。 同样，我们的组织也必须认识到这种偏见的存在，并努力在他们的员工队伍、产品开发和用户外展中解决它。
<details> <summary>英文原文</summary><div style="border:1px solid #eee;padding:5px;background-color:#F2F2F2">
When engineers do not focus on users of different nationalities, ethnicities, races, genders, ages, socioeconomic statuses, abilities, and belief systems, even the most talented staff will inadvertently fail their users. Such failures are often unintentional; all people have certain biases, and social scientists have recognized over the past several decades that most people exhibit unconscious bias, enforcing and promulgating exist‐ ing stereotypes. Unconscious bias is insidious and often more difficult to mitigate than intentional acts of exclusion. Even when we want to do the right thing, we might not recognize our own biases. By the same token, our organizations must also recognize that such bias exists and work to address it in their workforces, product development, and user outreach.
</div></details>
由于偏见，谷歌有时未能在其产品中公平地代表用户，过去几年的发布并没有充分关注代表性不足的群体。 许多用户将我们在这些情况下缺乏意识归因于我们的工程人口主要是男性，主要是白人或亚洲人，当然不能代表使用我们产品的所有社区。 在我们的员工队伍中缺乏此类用户的代表性[^1]意味着我们通常没有必要的多样性来了解我们产品的使用如何影响代表性不足或易受伤害的用户。
<details> <summary>英文原文</summary><div style="border:1px solid #eee;padding:5px;background-color:#F2F2F2">
Because of bias, Google has at times failed to represent users equitably within their products, with launches over the past several years that did not focus enough on underrepresented groups. Many users attribute our lack of awareness in these cases to the fact that our engineering population is mostly male, mostly White or Asian, and certainly not representative of all the communities that use our products. The lack of representation of such users in our workforce[^1] means that we often do not have the requisite diversity to understand how the use of our products can affect underrepresented or vulnerable users.
</div></details>
<details>

<summary>Case Study: Google Misses the Mark on Racial Inclusion</summary>

In 2015, software engineer Jacky Alciné pointed out\[^2] that the image recognition algorithms in Google Photos were classifying his black friends as “gorillas.” Google was slow to respond to these mistakes and incomplete in addressing them.

What caused such a monumental failure? Several things:

* Image recognition algorithms depend on being supplied a “proper” (often mean‐ ing “complete”) dataset. The photo data fed into Google’s image recognition algorithm was clearly incomplete. In short, the data did not represent the population.
* Google itself (and the tech industry in general) did not (and does not) have much black representation,\[^3] and that affects decisions subjective in the design of such algorithms and the collection of such datasets. The unconscious bias of the organization itself likely led to a more representative product being left on the table.
* Google’s target market for image recognition did not adequately include such underrepresented groups. Google’s tests did not catch these mistakes; as a result, our users did, which both embarrassed Google and harmed our users.

As late as 2018, Google still had not adequately addressed the underlying problem.\[^4]

</details>
在这个例子中，我们的产品设计和执行不充分，未能正确考虑所有种族群体，因此，我们的用户失败了，并给谷歌造成了负面新闻。 其他技术也有类似的失败：自动完成可能会返回令人反感或种族主义的结果。 谷歌的广告系统可能会被操纵以显示种族主义或冒犯性广告。 YouTube 可能不会捕捉到仇恨言论，尽管从技术上讲它在该平台上是非法的。
<details> <summary>英文原文</summary><div style="border:1px solid #eee;padding:5px;background-color:#F2F2F2">
In this example, our product was inadequately designed and executed, failing to properly consider all racial groups, and as a result, failed our users and caused Google bad press. Other technology suffers from similar failures: autocomplete can return offensive or racist results. Google’s Ad system could be manipulated to show racist or offensive ads. YouTube might not catch hate speech, though it is technically outlawed on that platform.
</div></details>
在所有这些情况下，技术本身并不是真正的罪魁祸首。 例如，自动完成并非旨在针对用户或进行歧视。 但它的设计也没有足够的弹性来排除被认为是仇恨言论的歧视性语言。 结果，该算法返回的结果对我们的用户造成了伤害。 对谷歌本身的伤害也应该是显而易见的：降低了用户对公司的信任和参与度。 例如，黑人、拉丁裔和犹太裔申请人可能会对 Google 作为一个平台甚至是一个包容性环境本身失去信心，从而破坏 Google 提高招聘代表性的目标。
<details> <summary>英文原文</summary><div style="border:1px solid #eee;padding:5px;background-color:#F2F2F2">
In all of these cases, the technology itself is not really to blame. Autocomplete, for example, was not designed to target users or to discriminate. But it was also not resilient enough in its design to exclude discriminatory language that is considered hate speech. As a result, the algorithm returned results that caused harm to our users. The harm to Google itself should also be obvious: reduced user trust and engagement with the company. For example, Black, Latinx, and Jewish applicants could lose faith in Google as a platform or even as an inclusive environment itself, therefore under‐ mining Google’s goal of improving representation in hiring.
</div></details>
这怎么可能发生？ 毕竟，谷歌聘用的技术人员具有无可挑剔的教育和/或专业经验——编写最好的代码并测试他们的工作的优秀程序员。 “为每个人打造”是 Google 的品牌宣言，但事实是，我们还有很长的路要走，才能宣称我们做到了。 解决这些问题的一种方法是帮助软件工程组织本身看起来像我们为其构建产品的人群。
<details> <summary>英文原文</summary><div style="border:1px solid #eee;padding:5px;background-color:#F2F2F2">
How could this happen? After all, Google hires technologists with impeccable education and/or professional experience—exceptional programmers who write the best code and test their work. “Build for everyone” is a Google brand statement, but the truth is that we still have a long way to go before we can claim that we do. One way to address these problems is to help the software engineering organization itself look like the populations for whom we build products.
</div></details>