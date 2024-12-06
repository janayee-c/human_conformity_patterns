# Human Conformity Patterns - A Monte Carlo Markov Chain Analysis

We decided to model our components based on the "OCEAN" or "Big Five" personality model. This model substantiates the following traits of *openness, conscientiousness, extraversion, agreeableness, and neuroticism*. Each of these traits relate to conformity in some shape or form; the participant's collaborative style and proclivity to assume the position of fellow confederates is largely dependent on self-esteem and social disposition constituted by the OCEAN personalities. For this exploration, we will be assuming that an individual whill exhibit a 'primary' and discrete trait that determines overall behaviour in teh experiment. Additionally, the traits will have error rates correspoding to their relationship to conformist behaviour.


> #### **Openness**
> - **Definition:** Openness characterizes an individual's willingness to experience a variety of activities, thoughtfulness, imagination, and curiosity.
>
> - **Relation to Conformity:**  Individuals with high openness might be less likely to conform due to their preference for exploring novel ideas and perspectives, and a lesser fear of standing out or being different. Relative to neurotic, agreeable and extroverted individuals, people who possess the primary trait of openness are less susceptible to errors due to their consideration of multiple perspectives and abstract concepts that do not necessarily conform with the majority.
> - **Error Rate:** 0.3


> #### **Conscientiousness**
> - **Definition:** Conscientiousness describes an individual's degree of organization, dependability, and diligence.
>
> - **Relation to Conformity:** Highly conscientious individuals might exhibit lower rates of conformity in situations that conflict with their internal standards or sense of responsibility, but might conform to adhere to rules or organized systems. Conscientious indviduals can fall in the group of *withdrawn* independents that exhibit non-conforomity rooted in personal values and individuality. Contrarily, conscientious individuals could also fall under the *distortion of action* conformists that conform due to the inability to incite disorder or experience inadequacy in regard to social duty. Thus, their error rate can be described as the closest to the median of the five OCEAN traits.
> - **Error Rate:** 0.5

> #### **Extraversion**
> - **Definition:** Extraversion is characterized by outgoingness, high energy levels, sociability, and the tendency to seek stimulation in the company of others.
>
> - **Relation to Conformity:** Extraverts might be more inclined to conform due to their high value on social relationships and being liked or accepted by others. They may conform to maintain positive social dynamics. Extraverts can either fall into the category of *confident* independents that are comfortable in social situations; alternatively, *distortion of action* resulting in conformity may also impact extraverts who feel that they cannot appear different or inferior from the majority.
> - **Error Rate:** 0.6

> #### **Agreeableness**
> - **Definition:** Agreeableness refers to an individual's propensity to be
compassionate, cooperative, and friendly toward others.
>
> - **Relation to Conformity:** Individuals with high agreeableness may be more inclined to conform in group settings to maintain harmony and positive relationships. Agreeable individuals have a higher error rate relative to those who possess conscientious as their primary traits due to their value of collective opinion. Thus, agreeable individuals are susceptible to conformity by *distortion of judgement and action.*
> - **Error Rate:** 0.7

> #### **Neuroticism**
> - **Definition:** Neuroticism is a trait characterized by emotional instability, anxiety, moodiness, and a higher propensity for negative emotions.
>
> - **Relation to Conformity:** Individuals with high levels of neuroticism might be more likely to conform due to fears of rejection or conflict, and a higher sensitivity to the opinions of others. Lower self-esteem and stress sensitivity contributes to further susceptibility and decision-making upon impulse, causing neurotic individuals to have the highest error rate out of the five OCEAN personality traits when in a relation of radical conflict with other members of a group. Neurotic individuals fall within the yielding group that distort perception, judgement and action due to lack of confidence.
> - **Error Rate:** 0.8
<br>

### Selecting Weights
- There wasn't much research to develop intuition on how we might start assigning weight values. However, we were able to find the graph below from a paper exploring Psychological Profiling of digital footprints.

- From the general shapes of the peaks of the graph, we derived our corresponding weights while also accounting for the demographic of the Asch experiment which would intuitively have higher rates of extraversion and agreeableness.
