# assignment-5-cs-754-advanced-image-processing-solved
**TO GET THIS SOLUTION VISIT:** [Assignment 5: CS 754, Advanced Image Processing Solved](https://www.ankitcodinghub.com/product/assignment-5-cs-754-advanced-image-processing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110531&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Assignment 5: CS 754, Advanced Image Processing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Consider an inverse problem of the form y = H(x) + η where y is the observed degraded and noisy image, x is the underlying image to be estimated, η is a noise vector, and H represents a transformation operator. In case of denoising, this operator is represented by the identity matrix. In case of compressed sensing, it is the sensing matrix, and in case of deblurring, it represents a convolution. The aim is to estimate x given y and H as well as the noise model. This is often framed as a Bayesian problem to maximize p(x|y,H) ∝ p(y|x,H)p(x). In this relation, the first term in the product on the right hand side is the likelihood term, and the second term represents a prior probability imposed on x.

With this in mind, we refer to the paper ‘User assisted separation of reflections from a single image using a sparsity prior’ by Anat Levin, IEEE Transactions on Pattern Analysis and Machine Intelligence. Answer the following questions:

In Eqn. (7), explain what Aj→ and bj represent, for each of the four terms in Eqn. (6).

In Eqn. (6), which terms are obtained from the prior and which terms are obtained from the likelihood? What is the prior used in the paper? What is the likelihood used in the paper?

Why does the paper use a likelihood term that is different from the Gaussian prior? [7+12+6=25 points]

2. Consider compressive measurements of the form y = Φx + η under the usual notations with y

). Instead of the usual model of assuming signal sparsity in an

orthonormal basis, consider that x is a random draw from a zero-mean Gaussian distribution with known covariance matrix Σx (of size n × n). Derive an expression for the maximum a posteriori (MAP) estimate of x given y,Φ,Σx. Also, run the following simulation: Generate Σx = UΛUT of size 128 × 128 where U is a random orthonormal matrix, and Λ is a diagonal matrix of eigenvalues of the form ci−α where c = 1 is a constant, i is an index for the eigenvalues with 1 ≤ i ≤ n and α is a decay factor for the eigenvalues. Generate 10 signals from N(0,Σx). For m ∈ {40,50,64,80,100,120}, generate compressive measurements of the form y = Φx + η for each signal x. In each case, Φ should be a matrix of iid Gaussian entries with mean 0 and variance 1/m, and σ = 0.01× the average absolute value in Φx. Reconstruct x using the MAP formula, and plot the average RMSE versus m for the case α = 3 and α = 0. Comment on the results – is there any difference in the reconstruction performance when α is varied? If so, what could be the reason for the difference? [25 points]

1

4. Read section 1 of the paper ‘Exact Matrix Completion via Convex Optimization’ from the homework folder.Answer the following questions: (1) Why do the theorems on low rank matrix completion require that the singular vectors be incoherent with the canonical basis (i.e. columns of the identity matrix)? (2) How would this coherence condition change if the sampling operator were changed to the one in Eqn. 1.13 of the paper?

[10 points]

5. Read section 5.9 of the paper ‘Low-Rank Modeling and Its Applications in Image Analysis’ from the homework folder. You will find numerous image analysis or computer vision applications of low rank matrix modelling and/or RPCA, which we did not cover in class. Your task is to glance through any one of the papers cited in this section and answer the following: (1) State the title and venue of the paper; (2) Briefly explain the problem being solved in the paper; (3) Explain how low rank matrix recovery/completion or RPCA is being used to solve that problem. Write down the objective function being optimized in the paper with meaning of all symbols clearly explained. [5 + 10 = 15 points]

2
