# What Text Features Drive Instagram Engagement: A Practice on Perfume

On social media, influencer marketing has become a key strategy for promoting beauty and lifestyle products—especially perfumes. To better understand what drives engagement in this niche, I conducted an in-depth textual analysis of five Instagram influencers who focus exclusively on perfume-related content. The results reveal that perfume marketing on social media thrives on emotional storytelling and subtle cues that spark user interaction. While likes can be easily driven by visual aesthetics and emoji usage, comments require deeper emotional and cognitive stimulation, conveyed through captions, image choices, and thoughtful language.

<img width="1161" height="653" alt="image" src="https://github.com/user-attachments/assets/2cbbabe7-9002-4767-b93a-ccb1979cde7d" />

<img width="1160" height="653" alt="image" src="https://github.com/user-attachments/assets/b6c6a126-ab58-47a4-b562-3b3bfd28e12d" />

**Content Has a Stronger Effect on Comments than Likes**
One of the core findings is that comments are more significantly influenced by content factors than likes. This suggests that prompting users to comment involves more active engagement than receiving passive approval through likes. For example, including perfume bottles in images (without people or “branded selfies” like hands holding products) enhances comment activity. Similarly, darker-toned images with lower saturation and contrast tend to spark more discussion.

**Captions That Spark Engagement**
The style and tone of captions are essential. Posts written with a positive tone, strong emotional language, and questions tend to perform better in generating comments. Moreover, longer captions—especially those that invite dialogue—correlate with higher comment counts. In contrast, likes are more easily influenced by simple tactics like inserting emojis and maintaining an overall upbeat tone.

**Themes Don’t Predict Engagement, but Words Do**
Using Latent Dirichlet Allocation (LDA), I identified five common themes in influencer captions:
Sharing personal fragrance experiences
Product and brand mentions
Sensory and emotional impressions
Fragrance note reviews
Collection and preference expressions
Interestingly, topic probabilities had no significant effect on engagement, likely due to the homogeneity of the niche content. Perfume posts tend to be visually driven and stylistically similar, making textual themes less differentiating. However, frequently used keywords in captions do have a positive effect on comment counts—proving that word choice still matters, even when overall themes are constant.

**Emojis and Punctuation Matter**
Textual elements such as emoji usage and punctuation also showed strong influence:
Emojis significantly increase both likes and comments.
Question marks have a positive impact on comment activity.
Surprisingly, hashtags and exclamation marks showed no significant effect on engagement.

**Emotional Tone Drives Engagement**
To analyze emotional tone, I applied four sentiment analysis tools: AFINN, LIWC, Syuzhet, and Sentimentr. The findings highlight the importance of emotional richness and contrast in stimulating engagement:
A higher AFINN score (positive sentiment) boosts likes.
The presence of negative words (from LIWC) correlates with increased comments, likely because they evoke stronger reactions.
A higher Syuzhet score (emotional intensity) also raises comment engagement.
Conversely, a high Sentimentr score (mild positivity) is negatively correlated with comments, suggesting that bland positivity lacks emotional pull.
