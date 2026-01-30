*The dataset and code will be released after the paper is accepted!!!*
*Abstract*
Existing methods for farmland remote sensing image 001
(FRSI) segmentation generally follow a static segmenta- 002
tion paradigm, where analysis relies solely on the limited 003
information contained within a single input patch. Con- 004
sequently, their reasoning capability is limited when deal- 005
ing with complex scenes characterized by ambiguity and vi- 006
sual uncertainty. In contrast, human experts, when inter- 007
preting remote sensing images in such ambiguous cases, 008
tend to actively query auxiliary images (such as higher- 009
resolution, larger-scale, or temporally adjacent data) to 010
conduct cross-verification and achieve more comprehen- 011
sive reasoning. Inspired by this, we propose a reasoning- 012
query-driven dynamic segmentation framework for FRSIs, 013
named FarmMind. This framework breaks through the lim- 014
itations of the static segmentation paradigm by introduc- 015
ing a reasoning-query mechanism, which dynamically and 016
on-demand queries external auxiliary images to compen- 017
sate for the insufficient information in a single input image. 018
Unlike direct queries, this mechanism simulates the think- 019
ing process of human experts when faced with segmenta- 020
tion ambiguity: it first analyzes the root causes of segmen- 021
tation ambiguities through reasoning, and then determines 022
what type of auxiliary image needs to be queried based 023
on this analysis. Extensive experiments demonstrate that 024
FarmMind achieves superior segmentation performance 025
and stronger generalization ability compared with existing 026
methods.
