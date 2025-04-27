# stor390-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [STOR390 Homework 6 Solved](https://www.ankitcodinghub.com/product/stor-390-homework-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122166&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STOR390 Homework 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Abstract: This homework explores optimization methods in machine learning, specifically Gradient Descent (GD) and Stochastic Gradient Descent (SGD), and their fundamental differences, particularly in the context of the update step. Additionally, it delves into the FedAve algorithm, presenting a proof of equivalence between two of its formulations and offering an intuitive explanation of its federated learning approach. Lastly, it examines the harm principle’s relevance to machine learning, questioning the agency of ML models and their potential to limit user autonomy through the unintended consequences of their application.

Question 1

What is the difference between gradient descent and stochastic gradient descent as discussed in class? (You need not give full details of each algorithm. Instead you can describe what each does and provide the update step for each. Make sure that in providing the update step for each algorithm you emphasize what is different and why.)

𝜃𝑖+1 = 𝜃𝑖 − 𝛼∇𝑓(𝜃𝑖,𝑥,𝑦)

𝜃𝑖+1 = 𝜃𝑖 − 𝛼∇𝑓(𝜃𝑖,𝑥′,𝑦′)

Here, (𝑥′,𝑦′) is a randomly chosen sample from the dataset, and ∇𝑓(𝜃𝑖,𝑥′,𝑦′) represents the gradient of the cost function with respect to 𝜃 for that sample. The main difference in SGD from GD lies in the granularity of data used to compute the gradient, making SGD faster and more memory-efficient, particularly for large datasets since each step uses a lesser amount of data than would be used in GD. Both methods aim to reach the cost function’s minimum, with GD providing a more stable but computationally intensive path, and SGD offering a faster, albeit potentially erratic, approach. The choice between them depends on the specific requirements and constraints of the machine learning problem at hand.

Question 2

Consider the ‘FedAve‘ algorithm. In its most compact form we said the update step is 𝜔𝑡+1 = 𝜔𝑡 −

𝜂∑𝐾𝑘=1 𝑛𝑛𝑘∇𝐹𝑘(𝜔𝑡). However, we also emphasized a more intuitive, yet equivalent, formulation given by

𝜔𝑡+1𝑘 = 𝜔𝑡 − 𝜂∇𝐹𝑘(𝜔𝑡);𝑤𝑡+1 = ∑𝐾𝑘=1 𝑛𝑛𝑘𝑤𝑡+1𝑘 . Prove that these two formulations are equivalent. (Hint: show that if you place 𝜔𝑡+1𝑘 from the first equation (of the second formulation) into the second equation (of the second formulation), this second formulation will reduce to exactly the first formulation.)

Proof that the two formulations are equivalent:

Start with the local update step from the second formulation below,

𝜔𝑡+1𝑘 = 𝜔𝑡 − 𝜂∇𝐹𝑘(𝜔𝑡)

Plug 𝜔𝑡+1𝑘 into the global aggregation step below,

𝐾

𝑛𝑘𝜔𝑡+1𝑘 )

𝜔𝑡+1 = ∑( 𝑛

𝑘=1

Substitute 𝜔𝑡+1𝑘 from the local update into the aggregation step such that,

𝐾

𝑛𝑘 (𝜔𝑡 − 𝜂∇𝐹𝑘(𝜔𝑡)))

𝜔𝑡+1 = ∑( 𝑛

𝑘=1

Distribute the summation over the terms inside the parentheses such that,

𝐾 𝐾

𝑛

𝜔𝑡+1 = ∑( 𝑛𝑘𝜔𝑡) − ∑(𝑛𝑛𝑘𝜂∇𝐹𝑘(𝜔𝑡))

𝑘=1 𝑘=1

Since ∑𝐾𝑘=1 𝑛𝑛𝑘 = 1, the first term simplifies to 𝜔𝑡, leading to:

𝐾

𝑛𝑘∇𝐹𝑘(𝜔𝑡))

𝜔𝑡+1 = 𝜔𝑡 − 𝜂∑( 𝑛

𝑘=1

This final expression is identical to the compact form of the FedAve update rule given at the beginning, thus proving that the two formulations are equivalent.

Question 3

Now give a brief explanation as to why the second formulation is more intuitive. That is, you should be able to explain broadly what this update is doing.

The second formulation of the FedAve algorithm offers a more intuitive perspective by breaking down the update process into two steps. Firstly, it separates the local updatestep on each node (K total), where the model parameters 𝜔𝑡 are individually updated based on the local data and objectives of each node, represented by ∇𝐹𝑘(𝜔𝑡). This mirrors the real-world scenario where data remains on a client’s device for privacy reasons, and the computation is decentralized. Each client computes the gradient of their own loss function, reflecting how their local data suggests adjusting the model for better performance. Secondly, the globalaggregationstepcombinestheselocalupdatesinto a unified model update. This is achieved by weighting each local update 𝜔𝑡+1𝑘 by the proportion of data 𝑛𝑘/𝑛 that the client contributes to the total dataset, ensuring that clients with more data have a proportionally greater influence on the model update. This aggregation mimics the federated learning goal of learning a global model that benefits from all available data without actually sharing the data itself.

This formulation highlights the federated learning’s primaryobjective-localcomputationfollowedbyaglobalaggregation to preserve data privacy while benefiting from decentralized data sources. The intuitive formulation clearly outlines the distributed nature of learning and the collective effort in updating the model.

Question 4

Explain how the harm principle places a constraint on personal autonomy. Then, discuss whether the harm principle is currently applicable to machine learning models. (Hint: recall our discussions in the moral philosophy primer as to what grounds agency. You should in effect be arguing whether ML models have achieved agency enough to limit the autonomy of the users of said algorithms.)

The harm principle, articulated by John Stuart Mill in his seminal work ”On Liberty,” suggests that the only reason for which power can be rightfully exercised over any member of a civilized community, against their will, is to prevent harm to others. This principle places a constraint on personal autonomy by asserting that individuals are free to act as they wish unless their actions harm others (ie your right to swing your fist ends where my nose begins). In essence, it balances individual freedom with the welfare of others, establishing a boundary where personal freedom ends when it infringes on the rights and well-being of someone else.

Applying the harm principle to machine learning models would involve assessing whether these models can exercise autonomy in a way that could harm individuals, and therefore, whether their operation should be limited based on the harm they could potentially cause. This raises the question of agency in machine learning models. Agency, in moral philosophy, refers to the capacity of an entity to act independently and make free choices. Traditional discussions of agency focus on sentient beings, particularly humans, because of their ability to deliberate, make decisions, and understand the consequences of their actions. Machine learning models, despite their complexity and ability to make decisions or predictions based on data, do not possess consciousness, self-awareness, or the ability to deliberate in the moral or philosophical sense. They operate within the framework of their programming and the data provided to them, without an understanding of the moral weight of their ”decisions.”

However, the harm principle can still be relevant to the use of machine learning models insofar as it applies to the designers, operators, and users of these models. While the models themselves do not have agency yet, their applications can indeed cause harm—for instance, through biased decision-making processes (eg COMPAS), invasions of privacy (eg Data Extraction Attacks), or other negative impacts on individuals or groups. In this sense, the autonomy of those who deploy machine learning models is constrained by the harm principle such that they are morally and, increasingly, legally obligated to ensure that their use of these technologies does not harm others. This perspective suggests that while machine learning models do not possess agency in the sense required to apply the harm principle directly to them, the principle is highly relevant to their deployment and use. The harm principle should serve as an ethical guideline for developers, users, and regulators to prevent harm that the use of such models might cause, thus indirectly constraining personal autonomy in the development and application of AI technologies.
