Delivery of video through Internet was introduced in
1990 itself. It evolved from method to method be-
cause of the increase in the Internet bandwidth and the
growth of world wide web [2]. The timely delivery of data
was the great issue ever. The evolution starts with the
Real-Time transfer protocol (RTP) proposed by Internet
Engineering Task Force (IETF) and it worked well in man-
aged IP Networks. After that, the managed IP networks
are replaced by Content Delivery Network (CDN) and
it introduced a conflict in using RTP. Hence a need for
another server to control this RTP introduced.
The introduction of HTTP streaming was one that can
use the advantage of high internet bandwidth. HTTP
streaming provides transfer of large packets instead of
small chunks. And it can manage by CDN by standard op-
timization techniques and it is firewall friendly in contrast
with RTP. Becuase of these advantages HTTP stream-
ing became popular in commercial implementations. Ap-
pleâĂŹs HTTP Live Streaming (HLS) [3], MicrosoftâĂŹs
Smooth Streaming [3], and AdobeâĂŹs HTTP Dynamic
Streaming [4] all use HTTP streaming as their underlying
method of delivery. But each of these implementations
has it’s on manifest and segment formats. All we need
is nothing but a standardization which a standards-based
client to stream content from any standards-based server,
and it provides a interoperability between different servers
of different vendors. As a result new standard intro-
duced known as MPEG Dynamic Adaptive Streaming
over HTTP (MPEG-DASH), is currently at the Draft
International Standard stage. DASH is designed to be
codec-agnostic, but the specification recommends the use
of MPEG-4 files or MPEG-2 streams [6]. DASH adaptive
streaming is nothing but the audio as well as video con-
tents are split into different bit-rate chunks according to
the current network bandwidth the adaptive algorithm will
select the best audio and video chunk and serves to the
client. More advanced uses cases may include switching
between multiple camera views, 3-D multimedia content
streaming, video streams with subtitles and captions, dy-
namic ad-insertion, low latency live streaming, playback
of mixed streaming and pre-stored content, and others[2].
The MPEG-DASH specification is a feature-rich standard
with many additional features.
Fig. 1. QoE comparison on different current scenario,by Benjamin
Rainer Christian Timmerer and Christian Timmerer in Quality of
Experience of Web-based Adaptive HTTP Streaming Clients in Real-
World Environments using Crowdsourcing
Even though we have a good adaptive streaming
methodology the success of the system comes when it
has a good Quality of experience (QoE).Over the last
decade, the performance was measured and monitored
using a method called Quality of service (QoS), which
is a mechanism of assessment in the network. According# A-New-Approach-To-QoE-Based-Model-For-Mobile-Video-Streaming
A New Approach To QoE Based Model For Mobile Video Streaming
Introduction
Delivery of video through Internet was introduced in 1990s itself.
It evolved from method to method be-cause of the increase in the Internet bandwidth and the
growth of world wide web . The timely delivery of data
was the great issue ever. The evolution starts with the
Real-Time transfer protocol (RTP) proposed by Internet
Engineering Task Force (IETF) and it worked well in man-
aged IP Networks. After that, the managed IP networks
are replaced by Content Delivery Network (CDN) and
it introduced a conflict in using RTP. Hence a need for
another server to control this RTP introduced.
The introduction of HTTP streaming was one that can
use the advantage of high internet bandwidth. HTTP
streaming provides transfer of large packets instead of
small chunks. And it can manage by CDN by standard op-
timization techniques and it is firewall friendly in contrast
with RTP. Becuase of these advantages HTTP stream-
ing became popular in commercial implementations. Ap-
pleâĂŹs HTTP Live Streaming (HLS) [3], MicrosoftâĂŹs
Smooth Streaming [3], and Adobs HTTP Dynamic
Streaming [4] all use HTTP streaming as their underlying
method of delivery. But each of these implementations
has it’s on manifest and segment formats. All we need
is nothing but a standardization which a standards-based
client to stream content from any standards-based server,
and it provides a interoperability between different servers
of different vendors. As a result new standard intro-
duced known as MPEG Dynamic Adaptive Streaming
over HTTP (MPEG-DASH), is currently at the Draft
International Standard stage. DASH is designed to be
codec-agnostic, but the specification recommends the use
of MPEG-4 files or MPEG-2 streams [6]. DASH adaptive
streaming is nothing but the audio as well as video con-
tents are split into different bit-rate chunks according to
the current network bandwidth the adaptive algorithm will
select the best audio and video chunk and serves to the
client. More advanced uses cases may include switching
between multiple camera views, 3-D multimedia content
streaming, video streams with subtitles and captions, dy-
namic ad-insertion, low latency live streaming, playback
of mixed streaming and pre-stored content, and others[2].
The MPEG-DASH specification is a feature-rich standard
with many additional features.

However, the Internet Engineering Task Force (IETF)
standardization group defines the QoS as "a set of service
requirements to be met by the network while transporting
a flow". QoS does not consider the userâĂŹs perception. So
sometimes if we have a complete QoS but the user may not
be satisfied. According to figure 1, it clearly shows that the
popularity of streaming methods directly depends on the
QoE. In the figure, it depicts how the youtube as a better
acceptance than any other service providers because they
include QoE as a major part. QoE is a multidisciplinary
and a multidimensional concept. It involves concepts from
several fields including human-computer interaction, cog-
nitive and behavioral science, computer networks and
economics[].ITU-T defines QoE as: âĂIJThe overall ac-
ceptability of an application or service, as perceived sub-
jectively by the end-user.âĂİ ItâĂŹs worth noting that
ITU-T also considers the following statements: âĂIJQual-
ity of Experience includes the complete end-to-end system
effects (client, terminal, network, services infrastructure,
etc.)âĂİ and âĂŸâĂŸOverall acceptability may be influ-
enced by user expectations and context.âĂİ But ITU-T
does not define what it means by âĂIJcontextâĂİ and how
experts can measure usersâĂŹ âĂIJexpectationsâĂİ.So
a modeling including QoE is needed for a better user
experience. We know there are QoS parameters and QoE
parameters, selecting appropriate parameters and finding
a relation between them is a major part. The relationship
between these parameters are sometimes linear or non-
linear and hard to measure and document them. The QoE
modelling is nothing but create a model which can select
and model these parameters efficiently. In other words
models are something that are not simply classifying the
parameters but they will measure and predict them.
Hence there is a need of video quality prediction model
considering QoE. In this paper proposes a model which is
considering both subjective and objective parameters. The
model is reliable because the QoS parameters considered
and not taken as independent parameters. The depen-
dency between the objective and subjective parameters
are found for a better QoE prediction. Model is expres-
sive enough to capture the complex and non-monotonic
relationship between QoS and QoE. It takes consideration
of Regression models that assign a certain relationship
(linear, logistic, etc.) that are problematic. The model
proposed is scalable because as the network and user
experience evolves with time, the model should be able
to readily take new variables, and give relatively accurate
results.
report organization

