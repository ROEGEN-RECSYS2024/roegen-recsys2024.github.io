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
    width: 150px; /* Adjust size as necessary */
    height: 150px; /* Maintain aspect ratio */
    border-radius: 75px; /* Circular photos */
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
    .important-dates, .organizers, .program-committee {
        background-color: #e8f0fe;
        padding: 10px;
        border-radius: 5px;
        margin: 10px 0;
    }
    .important-dates h3, .organizers h3, .program-committee h3 {
        margin-top: 0;
    }
</style>
</head>
<body>

<div class="navbar">
    <a href="#home">Home</a>
    <a href="#submission-guidelines">Call for Papers</a>
    <a href="#important-dates">Important Dates</a>
    <a href="#program">Program</a>
</div>

<div class="header">
    <h1>The 1st Workshop on Risks, Opportunities, and Evaluation of Generative Models in Recommender Systems (ROEGEN@RECSYS'24)</h1>
    <em>Colocated with ACM Conference on Recommender Systems in Bari, Italy in October 2024</em>
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
            <li><b>Notification of Acceptance:</b> September 13, 2024</li>
            <li><b>Camera-Ready Submission:</b> September 20, 2024</li>
            <li><b>Workshop Date:</b> October 18, 2024</li>
        </ul>
    </div>

<div class="featured-speakers" id="speakers">
    <h2>Featured Speakers</h2>
    <div class="speaker">
        <a href="https://mchen24.github.io"><img src="https://mchen24.github.io/minminc_profile.jpeg" alt="Minmin Chen" class="speaker-photo"></a>
        <div class="speaker-info">
            <h3><a href="https://mchen24.github.io">Minmin Chen</a></h3>
            <p>Principal research scientist at Google Deepmind, USA</p>
        </div>
    </div>
    <div class="speaker">
        <img src="img/photo_jiaqiz_roegen_04162024.jpg" alt="Jiaqi Zhai" class="speaker-photo">
        <div class="speaker-info">
            <h3><a href="https://www.linkedin.com/in/jiaqizhai/">Jiaqi Zhai</a></h3>
            <p>Senior Research Scientist at Meta, USA</p>
            <h4>Actions Speak Louder than Words: Building the Next-Generation Recommendation Systems</h4>
            <p>Recommendation systems enable billions of people to make informed decisions on a daily basis in every single online content and e-commerce platforms. The scale of such systems has increased by close to 10,000x in the last few years. Despite these being the largest software systems on the planet, most Deep Learning Recommendation Models (DLRMs) scale with data but fail to scale with compute.</p>
            <p>We discuss alternative approaches vs classical DLRMs in this talk. We show that by reformulating the classical IR tasks, ranking and retrieval, as a generative modeling problem (“Generative Recommenders”), we can overcome expressiveness constraints in traditional sequential formulations. Together with new algorithms tailored for recommendation settings, we can improve offline and online metrics by double digit percentages vs SotA baselines while using significantly fewer features. To enable efficient scaling, we next present new algorithms that speed up training and inference by 10x-1000x, by leveraging inherent data redundancy in recommendations and algorithmically increasing sparsity.  The GR formulation and algorithms have improved offline and online metrics by double digit percentages vs SotA baselines on a large internet platform. More importantly, GRs overcome compute scaling bottlenecks in traditional DLRMs, and we observe scaling law in deployed billion-user scale recommendation systems for the first time, up to GPT-3/LLaMa-2 compute scale.</p>
        </div>
    </div>
    <div class="speaker">
        <a href="https://www.cs.toronto.edu/~cebly"><img src="img/craig-boutilier.jfif" alt="Craig Boutilier" class="speaker-photo"></a>
        <div class="speaker-info">
            <h3><a href="https://www.cs.toronto.edu/~cebly">Craig Boutilier</a></h3>
            <p>Senior Research Scientist at Google</p>
            <h4>Alignment in Recommendation Systems</h4>
        </div>
    </div>
    <div class="speaker">
        <a href="https://md.ekstrandom.net"><img src="https://md.ekstrandom.net/images/me/ekstrand-2022.jpg" alt="Michael Ekstrand" class="speaker-photo"></a>
        <div class="speaker-info">
            <h3><a href="https://md.ekstrandom.net">Michael Ekstrand</a></h3>
            <p>Assistant professor at Drexel University, USA</p>
            <h4>Responsible Recommendation in the Age of Generative AI</h4>
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

</body>
</html>
