# Semantic similarity of sentences using Google's Universal Sentence Embeddings

This code was copied from https://colab.research.google.com/github/tensorflow/hub/blob/master/examples/colab/semantic_similarity_with_tf_hub_universal_encoder.ipynb#scrollTo=MSeY-MUQo2Ha

with changes to:

- work on my Linux laptop with a GeForce GTX 1070 that only has 8GB of video RAM
- code added to print out similarity for pairs of test sentences

# Example output

````````
- sentence 1: Calif man pleads not guilty in girl kidnap case
- sentence 2: Calif. man pleads not guilty in terrorism case
  similarity: 0.39930767
- sentence 1: Motorists killed after Japanese tunnel collapses
- sentence 2: Cars trapped in tunnel collapse outside Tokyo
  similarity: 0.30847847
- sentence 1: Chinese shares close lower on Wednesday
- sentence 2: Chinese students attacked in France
  similarity: -0.094588995
- sentence 1: Red grapes and blueberries boost immune system, scientists say
- sentence 2: Red grapes, blueberries boost human immunity
  similarity: 0.4463483
- sentence 1: 2 police killed in eastern Afghan explosion
- sentence 2: At least 28 people die in Chinese coal mine explosion
  similarity: 0.07962251
- sentence 1: The Note's Must-Reads for Monday, November 25, 2013
- sentence 2: The Note's Must-Reads for Tuesday, October 8, 2013
  similarity: 0.68068516
- sentence 1: Lebanon businesses strike in protest at political impasse
- sentence 2: Tunisia president says confident can overcome political crisis
  similarity: -0.0041418076
- sentence 1: Indian police round up all five suspects in Mumbai rape case
- sentence 2: Mumbai police arrest fifth suspect in gang-rape case
  similarity: 0.5430909
- sentence 1: Security tightens for Thatcher funeral
- sentence 2: Security agencies worry about new terrorist threats in Kenya
  similarity: -0.19768381
- sentence 1: Google invests $200 million in Texas wind farm
- sentence 2: Google invests 200 million USD in Texas wind farm project
  similarity: 0.65295887
- sentence 1: Euro crisis is over, says France's Francois Hollande
- sentence 2: Eurozone debt crisis is over, says France's President
  similarity: 0.51832324
- sentence 1: Treasury proposal sees 1.5% increase in income tax
- sentence 2: Treasury proposes 1.5% income tax raise in budget
  similarity: 0.5561793
- sentence 1: EU Ministers of Employment and Social policy will discuss how to boost employment, integrate social and economic policies
- sentence 2: EU Ministers of Employment and Social policy to discuss employment boosting strategies
  similarity: 0.5621973
- sentence 1: Chinese lunar rover lands on moon
- sentence 2: China lands robot rover on moon
  similarity: 0.48293453
- sentence 1: Boy, 14, arrested for sex attacks around a university campus
- sentence 2: Two teenagers arrested after string of sex attacks on Manchester University campus
  similarity: 0.50594604
- sentence 1: Protests after George Zimmerman acquitted in Trayvon Martin case
- sentence 2: Zimmerman acquitted in slaying
  similarity: 0.46471077
- sentence 1: Maldives begins to vote in controversy-ridden presidential poll
- sentence 2: Crisis-hit Maldives holds new presidential poll
  similarity: 0.5271987
- sentence 1: Obama, Hollande Hail Transformed US-French Relationship
- sentence 2: Hollande arrives for US state visit
  similarity: 0.19261622
- sentence 1: Iran, IAEA Officials Meet Ahead of March Nuclear Deadline
- sentence 2: Iran, IAEA officials meet ahead of March nuclear deadline: ISNA
  similarity: 0.8564788
- sentence 1: Bombings kill 9 people in Iraqi capital
- sentence 2: Bombings kill 19 people in Iraq
  similarity: 0.5507344
- sentence 1: 10 Things to Know for Wednesday
- sentence 2: 10 Things to Know for Thursday
  similarity: 0.58842856
- sentence 1: New UN peacekeeping chief named for Central African Republic
- sentence 2: UN takes over peacekeeping in Central African Republic
  similarity: 0.43084723
- sentence 1: Oil falls in Asian trade
- sentence 2: Oil prices down in Asian trade
  similarity: 0.48362207
- sentence 1: Israeli forces detain Palestinian MP in Hebron
- sentence 2: Israeli forces detain 2 Palestinians in overnight arrest raids
  similarity: 0.5485754
- sentence 1: Israeli police clash with Palestinian protesters at sensitive Jerusalem holy site
- sentence 2: Israel Police Clash With Palestinians in Jerusalem
  similarity: 0.5657351
- sentence 1: 3 killed, 4 injured in Los Angeles shootings
- sentence 2: Five killed in Saudi Arabia shooting
  similarity: 0.32807207
- sentence 1: Scientists prove there is water on Mars
- sentence 2: Has Nasa discovered water on Mars?
  similarity: 0.40565026
- sentence 1: Pranab stresses need to strive for peace by nations
- sentence 2: WTO: India regrets action of developed nations
  similarity: 0.1377281
- sentence 1: Volkswagen skids into red in wake of pollution scandal
- sentence 2: Volkswagen's "gesture of goodwill" to diesel owners
  similarity: 0.025196135
- sentence 1: Obama is right: Africa deserves better leadership
- sentence 2: Obama waiting for midterm to name attorney general
  similarity: 0.08812535
- sentence 1: New video shows US police officers beating mentally-ill man
- sentence 2: New York police officer critically wounded in hatchet attack
  similarity: 0.2900542
````````
