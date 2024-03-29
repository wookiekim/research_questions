#Glossary of terms and expressions

1. Efficacy
* the ability to produce a desired or intended result.

2. Isotropic kernel (Convolutional?)
* Kernel which depends only on the distance of the kernel arguments
  * ex) Discretized Gaussian, Direc Delta

3. Spurious
* not being whwat is purports to be, false or fake
* Apprently but not actually valid
* illegitimate
  ex) "find reliable matches by suppressing spurious ones.."
  
4. Fortuitious (lottery hypothesis)
* Happened by accident/ luck
  * "..the importance of these **fortuitious** initializations"

5. commensurate
* corresponding to size or degree; in proportion
  * Salary will commensurate with experience
  
6. Conducive
* good for, helpful to
  * "new architectures and initialization schemes with the same properties that are conducive to learning"

7. Latent
* Existing but not yet developed or manifest; hidden or concealed

8. Proxy
* Figure that can be used to represent the value of something in a calculation
  * Proxy-anchor
  * We use the iteration at which the early-stopping criterion is met as a proxy for how quickly the network learns.
  
9. "performance immediately suffers"

10. "results are more pronounced"

11. prime (v)
* Prepare (something) ready for use or action
  * "It is possible that dropout-induced sparsity primes a network to be pruned"

12. evocative(a)
* bringing strong images, memories, or feelings to mind
  * "we study the hypothesis on networks evocative of the architectures and techniques used in practice"

13. "conjectured" (adv for conjecture)
* "Our conjectured explanation for this behaviour is as follows:"

14. regime
* A system or a planned way of doing things, especially one imposed from above
  * "We use the same training regime and hyperparams"

15. "Our empirical study of the existence and nature of winning tickets invites a number of follow-up questions" - Discussion

16. "Loss Landscape"
* The initialization might land in a region of the loss landscape that is particularly amenable to optimization

17. amenable
* capable of being acted upon in a particular way; **susceptible to**

18. Hypothesize
* "We hypothesize that"

19. foray
* A sudden attack or incursion into enemy territory, especially to obtain something; a raid
  * "As our first foray to Deep learning using PyTorch"

20. manifold
* A collection of points forming a certain kind of set, such as those of a topologically closed surface or an analog of this in three or more dimensions

21. "To the best of our knowledge"

22. Penultimate
* Second last
  * "Penultimate layer"

23. "Shed light upon"

24. logit
* The raw outputs (unnormalized)

25. desideratum (n)
* Something that is needed or wanted
  * "integrity was a desideratum"
  
26. canonical (a)
* (Mathematics) Relating to a general rule or standard formula
   * "..aligning features on a canonical space"

27. eschew (v)
* deliberately avoid using; abstain from.
  * "...which eschews the need for heuristic sorting..."

28. emulate
* reproduce the function or action of (a different computer, software system, etc.).
  * "..which uses A to emulate the kernel pixels in 2D convolution"

29. In essence
* basically and without regard for peripheral details; fundamentally.
  * "In essence, we argue that a small number of keypoints suffice..."

30. dyad (n)
* an operator which is a combination of two vectors.
* something that consists of two elements or parts.
  * ""the mother–child dyad"

31. ascribe to (p.v)
* attribute something to (a cause).
  * "which can probably be ascribed to the small voxel size used in..."

32. generality (n)
* a statement or principle having general rather than specific validity or force.
* vs generalizability?
  * generality is the quality of being general while generalizability is the quality of being generalizable.
  
33. Homography (of an image)
* is a transformation (3x3 matrix) that maps the points in one image to the corresponding points in the other image.

34. acuity(n)
* sharpness or keenness of thought, vision, or hearing.
* "which decreases spatial **acuity** and registration accuracy"

35. SE(N) : mathematical expression
* Special Euclidean Group (depending on dimension n of the space)
* "...minimizes a differentiable loss via gradient descent on the continuous SE(3)"

36. Veracity(n)
* conforms to facts
* "...to estimate the veracity of each correspondence"

37. Putative
* Generally considered or reputed to be
* "..matched to form a set of putative correspondences."

38. "refine the result by optimizing a **robust objective**"

39. odometry
* use of data from motion sensors to estimate change in position over time.

40. holistic (a)
* characterized by comprehension of the parts of something as intimately interconnected and explicable only by reference to the whole.
* "3D Semantic segmentation typically requuires a **holistic** representation of the scene"

41. "...succeed in capturing and encoding evidence hidden to hand-engineered descriptors"

42. decoupled (a)
* "..which they try to refine globally in a subsequent **decoupled** step"

43. formulate (v)
* create or devise methodically
* "we formulate the traditional two-stage approach in an end-to-end framework"

44. SO(N) : mathematical expression
* special orthogonal group
* group of all rotations about the originof N-dimensional Euclidean space under the operation of composition

45. circumvent (v)
* find a way around (an obstacle).
* "To **circumvent** that, Eq.3 can be robustified against outliers by..."

46. heteroscedastic (v)
* In stats, a vector of random variables is heteroscedastic if the **variability of the random disturbance is different across elements** of the vector.
* "..by introducing a **heteroscedastic** weighting matrix"

47. "Its derivation is provided in the supplementary material"
* I need to know how to be precise in providing proofs and outlines
* Mathematical induction..functional analysis?

48. "We first describe the architectures used to approximate (functions...)"
* All sub-architectures are used individually to model a function
* DO NOT just stack layers and add superficial extravagances
  * Always devise what each part of the architecture is for, what function they are trying to model.

49. encompassed (a)
* surround and have or hold within
* "we argue that some of the required information is encompassed in the features of the second-to-last layer of the registration block"

50. natural basis
* aka standard basis
* whose coordinates are all zero except one that equals 1 (ex [0 0 1])

51. Hard negative mining
* https://www.reddit.com/r/computervision/comments/2ggc5l/what_is_hard_negative_mining_and_how_is_it/
* Label "False Positives" as "negatives" and leverage this additional information
* consists of identifying training set examples which are given low prob by the model, but which should be high prob instead
* Adversarial examples may be helpful as hard negative mining (an opinion)

52. Concretely
* In a definitive or conclusive way (To be precise? 엄밀하게?)
* "Conretely, we fine an approximation of D by performing line-search to find the minimum c for which..."

53. Subtle (a)
* (especially of a change or distinction) so delicate or precise as to be difficult to analyze or describe.
* "A subtle, but essential detail is that..."

54. Lipschitz constant
* https://www.eee.hku.hk/~msang/Numerical_Lipschitz.pdf
* limits how fast the function can change, in other words, if there is no LIpschitz constant, the function can change extremely fast without border (ie becomes discontinuous)

55. anecdotal(a)
* (of an account) not necessarily true or reliable, because based on personal accounts rather than facts or research.

56. "We adopt the recent Neighbourhood Consensus Networks" "propose modifications to overcome their main limitations"
* can refer to a strong baseline straightaway

57. competitive results in...
* can be used when the results are not SoTA, but comparable.

58. detail(v)
* "We detail the proposed..."

59. As a section title, when reviewing an existing idea -> "Review: Neighbourhood Consensus Networks"

60. memory-intensive (a)
* high memory overhead.

61. "prohibitively large"
* "...they would still be prohibitively large"

62. de facto
* in fact
* "...have become the de facto standard"
* note: in italics

63. 'modest at best'
* another way of saying "marginal"
* "..performance gains obtained by... have been only modest at best"

64. full set of dense correspondences
* a way of referring to exhaustive correspondences between all features

65. "This work relates to several lines of research, which we review below"
* At the beginning of related work, as the only sentence.

66. tentative (a)
* not certain or fixed

67. amenable (a)
* susceptible to, capcable of being acted upon in a  particular way
* "In order to have an approach that is amenable to end-to-end training"

68. a priori (a)
* relating or denoting reasoning or knowledge which proceeds from **theoretical deduction** rather than from observation or experience
* "Determining the correct matches from..... is, a priori, a significant challenge"
* Note: in italics

69. "well-established techniques"
* referring to SIFT and other good methods

70. "This suggests that the limiting factor may not lie in establishing the correspondences AS MUCH AS IN choosing those that are best to recover the pose"
* saying that one thing seems to be important than the other

71. "the ~assumption is violated in practice"
* saying that a certain assumption does not always hold
* "violated in practice"

72. "which makes the optimization numerically **better behaved**"
* a way of saying numerically stable?
* needs a reference, or has to be obvious.

73. ostensibly
* apparently or purportedly, but perhaps not actually. 

74. "To avoid exhaustive annotation"
* to avoid the usage of strong supervisions, which require a lot of annotations

75. sub-optimal
* Close to optimal, but not optimal;
* can be better. Used to express "not the best approach"

76. "Needle-in-haystack" scenarios
* used in "Learning to find good correspondences"
* referring to cases where there are a lot of outliers (inliers being "needles")
* Refers to the fact that English idioms could come in handy if used appropriately

77. "This is where our approach shines"
* "shines"

78. "Our proposed module, which is **realized with** a stack of non-isotropic 4D convolutions...."
* "realized with"
* implemented using?

79. "It is also worth noting that..."
* Note that...
* It is to be noted that...

80. exemplify (v)
* be a typical example of
* give an example of

81. Tenent (aka tenet) (n)
* A tenet is a principle or belief honored by a person or, more often, a group of people.

82. disgress (v)
* leave the main subject temporarily in speech or writing.
* "I have disgressed a little from my orignial plan"

83. astute (a)
* having or showing an ability to accurately assess situations or people and turn this to one's advantage.

84. Ambient space (n)
* An ambient space or ambient configuration space is the space surrounding an object. 

85. preclude (v)
* ".,..precludes parallelization within training examples"
* prevent from happening; make impossible

86. Autoregression (n)
* is a time series model that uses observations from previous time steps as input to a regression equation to predict the value at the next time step.

87. desideratum (plural: desiderata) (n)
* something that is needed or wanted.
* "integrity was a desideratum"
* "Motivating our use of self-attention we consider three desiderata"

88. trump (v)
* beat (someone or something) by saying or doing something better.
* "..large scale training trumps inductive bias."

89. rendition (n)
* visual representation or reproduction
* synonyms: depiction, portrayal, representation, delineation

90. delineate (v)
* describe or portray (something) precisely
* indicate the exact position of (a border or boundary).

91. take with a grain of salt (expr)
* to understand that something is not completely true or right
* not take something too seriously
* accept, but with some reservations or skepticism

92. Lesion studies (n)
* remove single blocks from an already trained network during inference.
* such that the information has toflow through the skip connection

93. corroborate (v)
* confirm or give support to (a statement, theory, or finding)
* synonyms: confirm, verify, endorse, ratify

94. "We recall that"
* before detailing the technical details of a well-known operation
* "We recall that, given an image tensor....the output of a conv layer is given by..."

95. convolve (v)
* roll or coil together; entwine
* verb for convolution

95. conflate (v)
* combine into one
* "...suggest that conflating pre-training and architectural advances is misguided..."

96. equivocal (a)
* uncertain or questional in nature
* ambiguous
* "...perceived as an unequivocal(unambiguous) advancement over its predecessors"

 97. slew of 
 * a very large number of
 * "...a slew of downsides"

 96. potpourri of
 * a mixture of things

 97. crux
* the decisive or most important point at issue.

98. Hadamard product
* elementwise product.

99. Iverson Bracket
* [True ] == 1
* [False] == 0 

100. bifurcate(v)
* to fork, branch to two

101. aleatoric (v)
* random

102. nefarious (v)
* wicked or criminal

103. subsume (v)
* to include or absorb in something else
* "thereby subsumiuung the X into the training computational graph"

104. entwined (a)
* to be twisted together
* "optimization and generalization are entwined in DNNs"

105. paradigmatic (a)
* serving as a typical example of something]
* "A paradigmatic example of a memorization algorithm is k-nearest neighbors"

106. operationalize (v)
* put into operation or use
* "we operationalize the definition of "memorization" as the behaviour exhivited by DNNs trained on noise"

107. ethos (n)
* the characteristic spirit of a culture, era, or community as menifested in its beliefs and aspirations.
* "THe design ethos of DETR easily extend to more complex tasks."

108. purport(v)
* claim

109. ameliorate(v)
* 개선하다 (usually a problem)

110. proclivity (n)
* a tendency to choose or do something regularly; an inclination or predisposition toward a particular thing
* "...proclivity to stand more time on social media"
