<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ROEGEN@RECSYS2024</title>
<style>
    .featured-speakers {
    margin: 20px;
    padding: 20px;
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.speaker {
    display: flex;
    margin-top: 20px;
}

.speaker-photo {
    width: 150px;
    height: 150px;
    border-radius: 75px;
    margin-right: 20px;
}

.speaker-info {
    flex-grow: 1;
}

    body {
        background-color: #f0f4f8;
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 0;
        padding: 0;
    }
    .navbar {
        overflow: hidden;
        background-color: #333;
    }
    .navbar a {
        float: left;
        display: block;
        color: white;
        text-align: center;
        padding: 14px 20px;
        text-decoration: none;
    }
    .navbar a:hover {
        background-color: #ddd;
        color: black;
    }
    .header {
        background-color: #5c9ded;
        color: white;
        text-align: center;
        padding: 50px 20px;
    }
    .header h1 {
        font-size: 2.5em;
        margin: 0;
    }
    .header em {
        font-size: 1.2em;
    }
    .content {
        margin: 20px;
        padding: 20px;
        background-color: #ffffff;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h2, h3 {
        color: #333;
    }
    ul {
        list-style: disc;
        margin-left: 20px;
    }
    .speakers, .important-dates, .organizers, .program-committee {
        background-color: #e8f0fe;
        padding: 10px;
        border-radius: 5px;
        margin: 10px 0;
    }
    .speakers h3, .important-dates h3, .organizers h3, .program-committee h3 {
        margin-top: 0;
    }
}
</style>
</head>
<body>

<div class="navbar">
    <a href="#home">Home</a>
    <a href="#submission-guidelines">Call for Papers</a>
    <a href="#important-dates">Important Dates</a>
    <a href="#program">Program</a>
    <a href="#speakers">Featured Speakers</a>
    <a href="#papers">Accepted Papers</a>
</div>

<div class="header">
    <h1>The 1st Workshop on Risks, Opportunities, and Evaluation of Generative Models in Recommender Systems (ROEGEN@RECSYS'24)</h1>
    <em>Colocated with <a href="https://recsys.acm.org/recsys24" style="color: white;">ACM Conference on Recommender Systems</a> in Bari, Italy in October 2024</em>
</div>

<div class="content" id="home">
    <h2>Home</h2>
    <p>Generative models are changing the way we seek information online. Large language models (LLMs) such as Chat-GPT represent one successful application of generative models, leveraging vast amounts of texts encoded in their billion-scale parameters. Recommendation systems employing generative models go beyond LLMs, encompassing a broader range of models such as deep generative models (DGMs) trained directly on user-item interactions, multi-modal foundation models, and other non-LLM generative models. These models offer new opportunities in the field of recommender systems by enhancing how user preferences are learned, connecting us with vast amounts of information available on the Internet. They are capable of delivering more personalized and contextually relevant content, generating recommendations without reliance on narrowly defined datasets, and addressing the cold-start issue. Furthermore, these models significantly enhance the level of interactivity users have with recommender systems, boosting conversational capabilities.</p>

    <p>However, there is no “free cake”; new advantages bring new challenges and risks that must be addressed when using LLMs and other categories of DGMs. Some of these challenges are new (e.g., hallucination, out-of-inventory recommendations) and some are newly intensified due to the expanded capabilities of these systems (privacy, fairness and biases, security and robustness, manipulation, opacity, accountability, over-reliance on automation). A critical aspect of utilizing these technologies is to develop robust evaluation systems that can effectively assess the performance, fairness, and security of these Gen-RecSys. Proper evaluation is essential to ensure these systems are reliable and trustworthy, especially when dealing with sensitive user data and making impactful recommendations.</p>

    <p>This workshop will specifically focus on the <b><u>R</u>isks</b>, <b><u>O</u>pportunities</b>, and <b><u>E</u>valuation</b> in real-world Recommender System applications, aiming to cover a full spectrum of current challenges and advances. Additionally, the workshop invites discussions on the application of LLMs and Generative Models in specific tasks and areas such as Conversation, Explanation, Bundle Recommendation, among others. The discussions are encouraged as long as the goal pertains to some form of information seeking.</p>

    <h2 id="topics">Topics</h2>
    <p>This workshop will focus on the opportunities and challenges of Recommender Systems in real-world applications, structured around three key pillars: opportunities, risks and challenges, and evaluation and mitigation strategies. Discussions will cover topics such as data preprocessing, model evaluation, fairness, debiasing, cold-start problems, model distillation, and user interaction design. We also welcome stories of Recommender System usage in specific applications, such as E-commerce, Streaming Services, News, Social Media, and Personalized Marketing. The goal is to bring together industry and academia researchers to foster knowledge sharing and create discussions that pave the way to societally beneficial exploitation of this technology.</p>

    <h3>Opportunities</h3>
    <ul>
        <li>Integrating large language models and other (multimodal) pre-trained generative models to enhance recommender algorithms for user modeling.</li>
        <li>Generative recommendation using AI to help create personalized item content, such as advertisements, images, and micro-videos.</li>
        <li>Combining content generation and retrieval for personalized information seeking and presentation.</li>
        <li>Leveraging the advantages of generative models to improve traditional recommender tasks, including collaborative, sequential, cold-start, social, conversational, multimodal, and causal recommendation.</li>
        <li>Applications of generative model-enhanced recommender systems in various sectors, such as finance, streaming platforms, social networks, entertainment, music, e-commerce, education, fashion, and healthcare.</li>
    </ul>

    <h3>Risks and Challenges</h3>
    <ul>
        <li>Identifying and addressing the potential risks and challenges associated with deploying generative models in recommender systems.</li>
        <li>Challenges of hallucination and misinformation risks, particularly with the advent of sophisticated image generation models.</li>
        <li>Examining bias and fairness in models with a special emphasis on mitigating biases related to race, gender, or brands.</li>
        <li>Privacy implications of utilizing extensive data for model training.</li>
        <li>Technical challenges in achieving transparency, explainability, security challenges, accountability and user control in recommendations.</li>
        <li>Ensuring compliance with emerging ethical and legal standards.</li>
    </ul>

    <h3>Evaluation and Mitigation</h3>
    <ul>
        <li>Developing new benchmarks, evaluation metrics, and protocols to assess the efficacy, fairness, and security of generative models in recommender systems.</li>
        <li>Novel strategies for bias detection, measurement, and understanding.</li>
        <li>Red-teaming and ensuring recommendations are transparent, explainable, and safeguard user privacy.</li>
        <li>Evaluating the robustness, trustworthiness, and real-time performance of generative models across different domains and modalities.</li>
        <li>Designing evaluation methodologies to examine the usage of generative models in recommender systems, including human evaluation paradigms and interfaces.</li>
        <li>Novel approaches for (generative model) Alignment and RLHF for recommendation tasks.</li>
    </ul>

    <h2 id="submission-guidelines">Submission Guidelines for the Workshop</h2>
    <p>We welcome submissions in the form of full papers, short papers, and extended abstracts that address any of the listed topics and related areas. Submissions should clearly articulate the contribution to the field, methodology, results, and implications for the design, implementation, or understanding of LLMs and Generative models in recommender systems. Submissions should follow the <a href="https://ceur-ws.org/Vol-XXX/CEURART.zip">CEUR-WS 2 column</a> (https://ceur-ws.org/Vol-XXX/CEURART.zip).</p>
    <ul>
        <li><b>Full Papers:</b> Full Papers (up to 8 pages, excluding references): Detailed studies, theoretical analyses, or extensive reviews of specific aspects of LLMs and Generative models in recommender systems.</li>
        <li><b>Short Papers:</b> (up to 4 pages, excluding references): Preliminary findings, innovative concepts, or case studies on the application of LLMs and Generative models in recommender systems.</li>
        <li><b>Extended Abstracts:</b> (2-3 pages, excluding references): Proposals for discussions, work-in-progress, or initial insights into the application of LLMs and Generative models in recommender systems.</li>
    </ul>
    <p>Submissions must be anonymized and adhere to the specified formatting guidelines, which will be provided on the workshop website.</p>
    <p>The submission site is <a href="http://easychair.org/my/conference?conf=recsys2024workshops">EasyChair RecSys 2024 Workshops</a>.</p>
    <p>Make sure to select the “The 1st Workshop on Risks, Opportunities, and Evaluation of Generative Models in Recommender Systems (ROEGEN@RECSYS'24)” track when creating a submission.</p>

    <p>All papers will undergo a rigorous double-blind peer review process, focusing on relevance, originality, technical quality, relation to the workshop scope, and overall contribution to the field. Acceptance will be based on these criteria. Accepted papers will be presented at the workshop and included in the proceedings, and will be published in CEUR Workshop Proceedings. All papers will undergo the same review process and review period. High-quality submissions will be recommended for a special issue in ACM TORS on using generative models for recommendation.</p>

    <div class="important-dates" id="important-dates">
        <h2>Important Dates</h2>
        <ul>
            <li><b>Submission Deadline:</b> <del><b>September 5, 2024</b></del> <span style="color:red;"><b>September 7, 2024 Final (AOE)</b></span></li>
            <li><b>Notification of Acceptance:</b> <del><b>September 13, 2024</b></del> <span style="color:red;"><b>September 20, 2024</b></span></li>
            <li><b>Camera-Ready Submission:</b><del><b>September 20, 2024</b></del> <span style="color:red;"><b>September 27, 2024</b></span></li>
            <li><b>Workshop Date:</b> October 18, 2024</li>
        </ul>
    </div>

<div class="program" id="program">
    <h2>Program Schedule</h2>
        <table border="1" cellpadding="5">
          <tr>
            <th>Time</th>
            <th>Event</th>
          </tr>
          <tr>
            <td>09:00-09:45</td>
            <td>Invited Talk – Michael Ekstrand (Drexel University): <i>Responsible Recommendation in the Age of Generative AI</i></td>
          </tr>
          <tr>
            <td>09:45-10:30</td>
            <td>
              Contributed Paper Talks:
              <ul>
                <li>09:45 – <i><a href="papers/recsys2024-workshops_paper_234.pdf">A Normative Framework for Benchmarking Consumer Fairness in Large Language Model Recommender Systems.</a></i> Fatemeh Nazary, Yashar Deldjoo.</li>
                <li>10:00 – <i><a href="papers/recsys2024-workshops_paper_222.pdf">A Prompting-Based Representation Learning Method for Recommendation with Large Language Models</a></i>. Junyi Chen, Toyotaro Suzumura.</li>
                <li>10:15 – <i><a href="papers/recsys2024-workshops_paper_224.pdf">Elaborative Subtopic Query Reformulation for Broad and Indirect Queries in Travel Destination Recommendation</a></i>. Qianfeng Wen, Yifan Liu, Joshua Zhang, George-Kirollos Saad, Anton Korikov, Yury Sambale, Scott Sanner.</li>
                <li>10:20 – <i><a href="papers/recsys2024-workshops_paper_184.pdf">Towards an explainable Argumentation-based Dialogue pipeline for Conversational Recommender Systems</a></i>. Marco Grazioso, Di Bratto Martina, Azzurra Mancini, Valentina Russo.</li>
                <li>10:25 – <i><a href="papers/recsys2024-workshops_paper_225.pdf">Cognitive Biases in Large Language Models for News Recommendation</a></i>. Yougang Lyu, Xiaoyu Zhang, Zhaochun Ren, Maarten de Rijke.</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td>10:30-11:00</td>
            <td>Coffee Break</td>
          </tr>
          <tr>
            <td>11:00-11:45</td>
            <td>Invited Talk – Craig Boutilier (Google Research): <i>Can Generative Models Improve Recommender Systems? Three Useful Notions of Alignment to Help with the Task</i></td>
          </tr>
          <tr>
            <td>11:45-12:30</td>
            <td>Invited Talk – Jianling Wang (Google DeepMind): <i>When LLMs Meet Recommendations: A Scalable Hybrid Approach</i></td>
          </tr>
          <tr>
            <td>12:30-14:15</td>
            <td>Lunch Break</td>
          </tr>
          <tr>
            <td>14:15-15:00</td>
            <td>Invited Talk – Aixin Sun (Nanyang Technological University): <i>Understanding and Evaluating Recommender Systems from a User Perspective</i></td>
          </tr>
          <tr>
            <td>15:00-15:45</td>
            <td>
              Contributed Paper Talks:
              <ul>
                <li>15:00 – <i><a href="papers/recsys2024-workshops_paper_70.pdf">Efficient and Responsible Adaptation of Large Language Models for Robust Top-k Recommendations</a></i>. Kirandeep Kaur, Chirag Shah.</li>
                <li>15:15 – <i><a href="papers/recsys2024-workshops_paper_144.pdf">Multilingual Prompts in LLM-Based Recommenders: Performance Across Languages</a></i>. Makbule Gulcin Ozsoy.</li>
                <li>15:30 – <i><a href="papers/recsys2024-workshops_paper_173.pdf">Towards Recommender Systems LLMs Playground (RecSysLLMsP): Exploring Polarization and Engagement in Simulated Social Networks</a></i>. Ljubisa Bojic, Zorica Dodevska, Yashar Deldjoo, Nenad Pantelic.</li>
                <li>15:35 – <i><a href="papers/recsys2024-workshops_paper_220.pdf">DaLimeLlama: a Persuasive XAI Framework for Learning-to-Rank Product Recommenders</a></i>. Sebastian Lubos, Seda Polat Erdeniz, Thi Ngoc Trang Tran, Alexander Felfernig, Ilhan Adiyaman, Tevfik Ince, Ata Gur.</li>
                <li>15:40 – <i><a href="papers/recsys2024-workshops_paper_145.pdf">Generative Diffusion Models for Sequential Recommendations</a></i>. Sharare Zolghadr, Ole Winther, Paul Jeha.</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td>15:45-16:15</td>
            <td>Coffee Break</td>
          </tr>
          <tr>
            <td>16:15-17:00</td>
            <td>Invited Talk – Jiaqi Zhai (Meta): <i>Actions Speak Louder than Words: Building the Next-Generation Recommendation Systems</i></td>
          </tr>
          <tr>
            <td>17:00-17:45</td>
            <td>
              Contributed Paper Talks:
              <ul>
                <li>17:00 – <i><a href="papers/recsys2024-workshops_paper_204.pdf">End-to-end Training for Recommendation with Language-based User Profiles</a></i>. Zhaolin Gao, Joyce Zhou, Yijia Dai, Thorsten Joachims.</li>
                <li>17:15 – <i><a href="papers/enrico_text2tracks.pdf">Text2Tracks: Generative Track Retrieval for Prompt-based Music Recommendation</a></i>. Enrico Palumbo, Gustavo Penha, Andreas Damianou, Jose Luis Redondo-García, Timothy Christopher Heath, Alice Wang, Hugues Bouchard, Mounia Lalmas.</li>
                <li>17:30 – <i><a href="papers/recsys2024-workshops_paper_208.pdf">Music Recommendation through LLM Song Summary</a></i>. Noah Tekle, Alline Ayala, Jonathan Haile, Abdulla Alshabanah, Corey Baker, Murali Annavaram.</li>
                <li>17:35 – <i><a href="papers/recsys2024-workshops_paper_223.pdf">Proactive Detection and Calibration of Seasonal Advertisements with Multimodal Large Language Models</a></i>. Hamid Eghbalzadeh, Shuai Shao, Saurabh Verma, Venugopal Mani, Hongnan Wang, Jigar Madia, Sean Obryne, Vitali Karpinchyk, Andrey Malevich.</li>
                <li>17:40 – <i><a href="papers/recsys2024-workshops_paper_226.pdf">On Data Contamination in Recommender Systems. Dario Garigliotti</a></i>.</li>
              </ul>
            </td>
          </tr>
        </table>
</div>

<div class="featured-speakers" id="speakers">
    <h2>Featured Speakers</h2>
    <div class="speaker">
        <img src="img/craig-boutilier.jfif" alt="Craig Boutilier" class="speaker-photo">
        <div class="speaker-info">
            <h3><a href="https://www.cs.toronto.edu/~cebly">Craig Boutilier</a></h3>
            <p>Principal Scientist at Google, USA</p>
            <h4>Can Generative Models Improve Recommender Systems? Three Useful Notions of Alignment to Help with the Task</h4>
            <p>Alignment is a broad notion that is often interpreted in various ways in the context of generative models (GenAI). This is due, in large part, to the staggering range of uses to which GenAI can be put. The application of Gen to recommender systems is no different: the variety of ways GenAI can be employed requires diverse perspectives on alignment. In this talk, I outline three uses of GenAI in recommenders that require distinct formulations of alignment: (a) GenAI in multi-modal, interactive recommenders; (b) GenAI for user simulation in recommenders; and (c) GenAI for filling in “content gaps,” i.e., generating novel items to better match the preferences of a user population. I briefly describe some work that tackles these three use cases (to varying degrees), and outline several significant research challenges that must be addressed to better exploit GenAI in the development of recommenders.</p>
        </div>
    </div>
    <div class="speaker">
        <img src="https://md.ekstrandom.net/images/me/ekstrand-2022.jpg" alt="Michael Ekstrand" class="speaker-photo">
        <div class="speaker-info">
            <h3><a href="https://md.ekstrandom.net">Michael Ekstrand</a></h3>
            <p>Assistant Professor at Drexel University, USA</p>
            <h4>Responsible Recommendation in the Age of Generative AI</h4>
            <p>Generative AI is bringing significant upheaval to how we think about and build recommender systems, both in the underlying recommendation techniques and in the design of surrounding applications and user experiences, with potentially profound impact on the social, ethical, and humanitarian impacts of recommendation. Some concepts developed for responsible recommendation, retrieval, and AI can be applied to generative recommendation, while others are substantially complicated or hindered by the significant changes in the relationships between users, creators, items, and platforms that generative AI brings. In this talk, I will argue that thinking clearly and explicitly about the underlying social, legal, and moral principles that responsible recommendation efforts seek to advance will provide guidance for thinking about how best to apply and revise impact concerns in the face of current and future changes to recommendation paradigms and applications.</p>
        </div>
    </div>
    <div class="speaker">
        <img src="img/aixin-sun.jpg" alt="Aixin Sun" class="speaker-photo">
        <div class="speaker-info">
            <h3><a href="https://personal.ntu.edu.sg/axsun">Aixin Sun</a></h3>
            <p>Associate Professor at Nanyang Technological University, Singapore</p>
            <h4>Understanding and Evaluating Recommender Systems from a User Perspective</h4>
            <p>Recommender Systems (RecSys) have garnered significant attention from both industry and academia for decades. This interest has led to the development of various solutions, ranging from classic models to deep learning and, more recently, generative models. Typically, the evaluation of these models relies on predefined RecSys research problems and available offline datasets. However, the user perspective of RecSys is often underemphasized. In this talk, I will share my understanding as a user of several RecSys systems, discussing the RecSys research problem and the expected evaluations. I believe that considering the user perspective can significantly influence our model design and evaluation, especially in the era of RecSys powered by generative models.</p>
        </div>
    </div>
    <div class="speaker">
        <img src="img/jianling-wang.jfif" alt="Jianling Wang" class="speaker-photo">
        <div class="speaker-info">
            <h3><a href="https://sites.google.com/view/jianlingwang">Jianling Wang</a></h3>
            <p>Senior Research Scientist at Google DeepMind, USA</p>
            <h4>When LLMs Meet Recommendations: A Scalable Hybrid Approach</h4>
            <p>While LLMs’ reasoning and generalization capabilities can aid higher level user understanding and longer term planning for recommendations, directly applying them to industrial recommendation systems have been shown challenging. The talk will cover our recent work on a hybrid approach to combine LLMs and classic recommendation models, and study its effectiveness for a challenging recommendation task on user exploration.</p>
        </div>
    </div>
    <div class="speaker">
        <img src="img/photo_jiaqiz_roegen_04162024.jpg" alt="Jiaqi Zhai" class="speaker-photo">
        <div class="speaker-info">
            <h3><a href="https://www.linkedin.com/in/jiaqizhai/">Jiaqi Zhai</a></h3>
            <p>Distinguished Engineer at Meta, USA</p>
            <h4>Actions Speak Louder than Words: Building the Next-Generation Recommendation Systems</h4>
            <p>Recommendation systems enable billions of people to make informed decisions on a daily basis in every single online content and e-commerce platforms. The scale of such systems has increased by close to 10,000x in the last few years. Despite these being the largest software systems on the planet, most Deep Learning Recommendation Models (DLRMs) scale with data but fail to scale with compute.</p>
            <p>We discuss alternative approaches vs classical DLRMs in this talk. We show that by reformulating the classical IR tasks, ranking and retrieval, as a generative modeling problem (“Generative Recommenders”), we can overcome expressiveness constraints in traditional sequential formulations. Together with new algorithms tailored for recommendation settings, we can improve offline and online metrics by double digit percentages vs SotA baselines while using significantly fewer features. To enable efficient scaling, we next present new algorithms that speed up training and inference by 10x-1000x, by leveraging inherent data redundancy in recommendations and algorithmically increasing sparsity.  The GR formulation and algorithms have improved offline and online metrics by double digit percentages vs SotA baselines on a large internet platform. More importantly, GRs overcome compute scaling bottlenecks in traditional DLRMs, and we observe scaling law in deployed billion-user scale recommendation systems for the first time, up to GPT-3/LLaMa-2 compute scale.</p>
        </div>
    </div>
</div>
    <div class="organizers">
        <h2>Workshop Organizers</h2>
        <ul>
            <li><a href="https://scholar.google.com/citations?user=-C_x_hUAAAAJ&hl=en">Yashar Deldjoo</a>, Tenure-Track Assistant Professor, Polytechnic University of Bari, Italy</li>
            <li><a href="https://scholar.google.com/citations?user=icbo4M0AAAAJ&hl=en">Julian McAuley</a>, Professor, UC San Diego, USA</li>
            <li><a href="https://scholar.google.com/citations?hl=en&user=kB8UPNIAAAAJ">Scott Sanner</a>, Associate Professor, University of Toronto, Canada</li>
            <li><a href="https://scholar.google.com/citations?hl=en&user=gu9fnxsAAAAJ">Pablo Castells</a>, Professor, Autonomous University of Madrid, Spain</li>
            <li><a href="https://scholar.google.com/citations?hl=en&user=PPjdxlcAAAAJ">Shuai Zhang</a>, Applied Scientist, Amazon Web Services AI, USA</li>
            <li><a href="https://scholar.google.com/citations?hl=en&user=WINnyNwAAAAJ">Enrico Palumbo</a>, Senior Research Scientist, Spotify</li>
        </ul>
    </div>

    <div class="program-committee">
        <h2>Program Committee</h2>
        <ul>
            <li>Aleksandr Petrov, a.petrov.1@research.gla.ac.uk, University of Glasgow</li>
            <li>Branislav Kveton, bkveton@amazon.com, Amazon</li>
            <li>Chao Zhang, zclfe00@gmail.com, University of Science and Technology of China</li>
            <li>Chengkai Huang, chengkai.huang1@unsw.edu.au, The University of New South Wales</li>
            <li>Chen Ma, chenma@cityu.edu.hk, City University of Hong Kong</li>
            <li>Claudia Hauff, claudia.hauff@gmail.com, Spotify</li>
            <li>Dietmar Jannach, dietmar.jannach@aau.at, University of Klagenfurt</li>
            <li>Gustavo Penha, gustavop@spotify.com, Spotify</li>
            <li>Hugues Bouchard, hb@spotify.com, Spotify</li>
            <li>Martin Mladenov, mmladenov@google.com, Google </li>
            <li>Michael Ekstrand, mde48@drexel.edu, Drexel University</li>
            <li>Mohammad Aliannejadi, m.aliannejadi@uva.nl, University of Amsterdam</li>
            <li>Narges Tabari, nargesam@amazon.com, Amazon</li>
            <li>Paolo Garza, paolo.garza@polito.it, Politecnico di Torino</li>
            <li>Reza Shirvany, reza.shirvany@zalando.de, Zalando</li>
            <li>Thong Nguyen, thongnguyen@microsoft.com, Microsoft</li>
            <li>Zhankui He, zhh004@ucsd.edu, University of California San Diego</li>
        </ul>
    </div>
</div>
<div class="accepted-papers" id="papers">
    <h2>Accepted Papers</h2>
    <ul>
        <li><a href="papers/enrico_text2tracks.pdf">"Text2Tracks: Generative Track Retrieval for Prompt-based Music
            Recommendation", Enrico Palumbo, Gustavo Penha, Andreas Damianou, José Luis Redondo García,
            Timothy Christopher Heath, Alice Wang, Hugues Bouchard and Mounia Lalmas</a></li>
    </ul>
</div>
</body>
</html>
