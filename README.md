# EmoSpeech

Speech is the most natural way of interaction between humans. Speech based devices
are used in our daily lives and are a boon for people with speech related disabilities.
Speech signals are a function of time variable which is independent and are random sig-
nals. Speech signal contains information about speech style, words, expression, accent
type, emotion, sex, age, speaker’s identity, the state of health of the speaker etc. Here
we are more interested in extracting emotions in speech.
In applications like professional driving or flying, or anything that requires continuous
monitoring of a persons emotion could use computers to encourage detection of emo-
tions, so as to upgrade the recognition procedure and to utilize such data to help improve
decisions and to support the basic leadership process. Up until this point, results emerg-
ing from machine feeling acknowledgment indicated better execution when contrasted
with human feeling acknowledgment.
Feeling acknowledgment from the speaker’s discourse is troublesome in light of the ac-
companying reasons: In separating between different feelings which specific discourse
highlights are increasingly valuable isn’t clear. As a result of the presence of various
sentences, speakers,style of speaking,rate of talking addressing fluctuation was intro-
duced,causing discourse highlights to legitimately get influenced. The same expression
may demonstrate various feelings. Every feeling may relate to the various segments
of the verbally expressed articulation. Accordingly it is hard to separate these bits of
articulation. Another problematic factor is the dependence of emotional expression on
the speaker and his or her culture and environment.The speaking style changes with the
culture and environment of the speaker which poses challenge for speech emotion recog-
nition systems. It is unclear whether the recognition system will detect the emotions
correctly when there are two or more types of emotions,long term and short term.
As there are six universal emotions anger, sad, happy, neutral, fear and disgusted but
we have not sufficient dataset for classifying all six emotions so we have classified four
emotions sad, happy, anger and neutral. The initial phase in getting machines to per-
ceive feelings is to accumulate information from which a machine will learn. This should
be possible by utilizing essential and optional inputs. The essential information could
be accounts of entertainers which express various feelings by perusing the equivalent
content, while the optional info could be utilizing as of now existing databases, which
were created by other scientists. Some half breed approaches are likewise conceiv-
able. The following stage would extricate highlights from gathered or obtained data.
Some acoustic features are intensity, pitch, loudness. The dataset we have used in
our project is Emo-DB which contains about 500 utterances spoken by actors in states
of fear,happiness,anxiety,boredom,angry and disgusted as well as neutral.In order to run
these different machine learning algorithms this Emo-DB dataset needs some preprocess-
ing steps which include padding, filtering etc. And for extracting features from speech
we used well known technique known as Mel Frequency Cepstral coefficients (MFCCs).
Mel frequency cepstral coefficients (MFCCs) is broadly utilized in discourse acknowl-
edgment and discourse feeling acknowledgment frameworks since acknowledgment rate
of the MFCC is generally amazing. MFCC can help us achieve better robustness and
frequency resolution to noise in low frequency region. Mel frequency cepstral illustrates
short term power spectrum of sound.
A computer program that decides whether an sample is a positive or negative is called
a classifier. A classifier is trained on hundreds of thousands of speeches to learn how
to classify a new speech correctly. We have used various machine learning and deep
learning classifiers in this project like Support Vector Machine(SVM), Random Forest
Classifier(RF), Multi Layer Perceptron(MLP), Convolutional Neural Networks(CNN) and
Long Short Term Memory(LSTM)
