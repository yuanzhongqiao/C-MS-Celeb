<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C-MS-名人</font></font></h1><a id="user-content-c-ms-celeb" class="anchor" aria-label="永久链接：C-MS-Celeb" href="#c-ms-celeb"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 MS-Celeb-1M 人脸数据集的干净版本，包含 94,682 位名人的 6,464,018 张图片。由于原始</font></font><a href="https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MS-Celeb-1M 中</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有太多错误标记的图片，我们希望清理此数据集以便更好地进行模型训练。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常感谢</font></font><a href="https://github.com/ha1990-12"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ha1990-12</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，原始 MS-Celeb-1M 数据集可</font></font><a href="https://academictorrents.com/details/9e67eb7cc23c9417f39778a8e06cca5e26196a97/tech&amp;hit=1&amp;filelist=1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获得。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的清理工作论文“一种清理超大人脸数据库的社区检测方法”可以</font></font><a href="https://www.hindawi.com/journals/cin/2018/4512473/abs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里找到</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据概览</font></font></h2><a id="user-content-data-overview" class="anchor" aria-label="永久链接：数据概览" href="#data-overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的 C-MS-Celeb 清理数据集包含 94,682 位名人的 6,464,018 张图片。下表将我们的数据集与其他公开的清理过的 MS-Celeb 数据集进行了比较：</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">名人</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图片</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">原始数据集</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">99,892</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8,456,240</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">XiangWu 的清理数据集</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">79,099</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5,049,824</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MS-Celeb-1M WashList 清理数据集</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">78,579</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4,621,640</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C-MS-Celeb 清理数据集</font></font></td>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">94,682</font></font></strong></td>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6,464,018</font></font></strong></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的 C-MS-Celeb</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">庞大、干净而且多样</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大的</font></font></h3><a id="user-content-large" class="anchor" aria-label="固定链接：大" href="#large"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，从这个表格中，我们可以看出，与其他清理列表相比，C-MS-Celeb在清理过程中保留了更多的人和更多的图像。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">干净的</font></font></h3><a id="user-content-clean" class="anchor" aria-label="永久链接：清洁" href="#clean"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其次，根据我们的实证评估，C-MS-Celeb 中大约 97.3% 的图像被正确标记。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">各种各样的</font></font></h3><a id="user-content-diverse" class="anchor" aria-label="固定链接：多样" href="#diverse"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第三，我们基于社区检测的清理方法还可以保留每个人脸部图像的多样性。以下是我们清理结果中来自“Lady Gaga”和“Quinn Cummings”的一些示例图像：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/JinRC/C-MS-Celeb/blob/master/sample_images.png"><img src="https://github.com/JinRC/C-MS-Celeb/raw/master/sample_images.png" width="600" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从这些样例结果中我们可以看到，不同妆容的图片在清洗过程中都能保留下来（左半部分为Lady Gaga），从清洗结果中也能观察到不同年龄段的多样性（右半部分为Quinn Cummings）。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的清理方法基于社区检测</font></font></h2><a id="user-content-our-cleaning-method-based-on-community-detection" class="anchor" aria-label="永久链接：我们基于社区检测的清理方法" href="#our-cleaning-method-based-on-community-detection"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们开发了一个基于社区检测的管道来清理嘈杂的 MS-Celeb-1M 人脸数据集。由于多个大型社区中保留了人脸的多样性，我们的清理结果既具有高清洁度，又具有丰富的数据多样性。更多详细信息可在我们的论文中</font></font><a href="https://www.hindawi.com/journals/cin/2018/4512473/abs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面的图片是菲尔·厄普丘奇在我们清理前后的照片</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/JinRC/C-MS-Celeb/blob/master/before_after.png"><img src="https://github.com/JinRC/C-MS-Celeb/raw/master/before_after.png" width="600" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">左侧带有红色方块的图像是 MS-Celeb-1M 人脸数据集中被错误标记的图像，右侧图像是我们清理的结果。我们可以再次看到，在清理过程中，各个年龄段的多样化 Phil Upchurch 被保留了下来。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下图说明了我们基于社区检测的清理方法。我们首先使用预先训练的人脸识别模型构建人脸相似度图。相似度图中的每个节点代表一张图片，两个节点之间的链接权重量化了这两张图片之间的相似度。然后我们删除弱链接并在该图上运行社区检测算法。最后，我们保留大社区中的图像（此图右侧的彩色社区），并删除分散节点和小社区（图中的灰色节点）。因此，我们能够在数据清理过程中实现高清洁度和丰富的数据多样性。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/JinRC/C-MS-Celeb/blob/master/community_detection_clean.png"><img src="https://github.com/JinRC/C-MS-Celeb/raw/master/community_detection_clean.png" width="600" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 C-MS-Celeb 训练人脸识别模型的好处</font></font></h2><a id="user-content-benefits-of-using-c-ms-celeb-to-train-a-face-recognition-model" class="anchor" aria-label="永久链接：使用 C-MS-Celeb 训练人脸识别模型的好处" href="#benefits-of-using-c-ms-celeb-to-train-a-face-recognition-model"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们使用 C-MS-Celeb 数据集来训练人脸识别模型，下图显示使用 C-MS-Celeb 进行模型训练可以提高模型的性能。查看</font></font><a href="https://www.hindawi.com/journals/cin/2018/4512473/abs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多好处详情。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/JinRC/C-MS-Celeb/blob/master/PR-curve.png"><img src="https://github.com/JinRC/C-MS-Celeb/raw/master/PR-curve.png" width="400" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用 C-MS-Celeb</font></font></h2><a id="user-content-how-to-use-c-ms-celeb" class="anchor" aria-label="永久链接：如何使用 C-MS-Celeb" href="#how-to-use-c-ms-celeb"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C-MS-Celeb在clean_list.7z中有两个TXT文件：“clean_list_128Vec_WT051_P010.txt”和“relabel_list_128Vec_T058.txt”，是清理后的脸部图像列表。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“clean_list_128Vec_WT051_P010.txt” 包含第 2 阶段所有清理结果的路径（有关详细信息，请参阅我们的论文）。“relabel_list_128Vec_T058.txt” 包含第 3 阶段所有重新标记结果的路径（有关详细信息，请参阅我们的论文）。对于这两个文件，第一列是图像的身份标签，第二列是图像文件的路径。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意这里的 C-MS-Celeb 只是清理后的标签列表。要使用此数据集，首先需要下载 MS-Celeb-1M 数据集的所有图像，然后根据 C-MS-Celeb 的 TXT 文件中的路径过滤掉噪声（错误标记）图像。您可能需要将这两个 TXT 文件合并为一个，然后过滤掉错误标记的图像。原始的 MS-Celeb-1M 数据集可在此网站下载：
 </font></font><a href="https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文信息</font></font></h2><a id="user-content-citation-information" class="anchor" aria-label="永久链接：引用信息" href="#citation-information"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用该数据集，请引用我们的论文：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chi Jin、Ruochun Jin、Kai Chen 和 Yong Dou，“一种清理超大规模人脸数据库的社区检测方法”，计算智能与神经科学，2018 年卷，文章 ID 4512473，10 页，2018 年。doi:10.1155/2018/4512473</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">@article{jin2018community，title={一种清理超大规模人脸数据库的社区检测方法}，author={Jin, Chi 和 Jin, Ruochun 和 Chen, Kai 和 Dou, Yong}，journal={计算智能与神经科学}，volume={2018}，year={2018}，publisher={Hindawi} }</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的论文“一种清理极大人脸数据库的社区检测方法”的链接是：
 </font></font><a href="https://www.hindawi.com/journals/cin/2018/4512473/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.hindawi.com/journals/cin/2018/4512473/</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另一项测试</font></font></p>
</article></div>
