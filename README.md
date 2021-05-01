# Speech Signal Processing (MADE S02E02)
This repository contains materials and notebooks for the Speech Signal Processing course.

**Tip #1:**

In case you don't want to load the entire repositiry, a single folder can be downloaded via [DownGit](https://downgit.github.io/).

**Tip #2:**

Sometimes GitHub failes to render a notebook. In that case use [nbviewer](https://nbviewer.jupyter.org/) — it works like a charm!

### Lectures

Course syllabus can be found [here](https://github.com/Illumaria/made-speech-signal-processing/blob/master/course_overview.pdf).

Legend: ![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png) — slides, ![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png) — code, ![](https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png) — video.

<table>
  <thead>
    <tr>
      <th>Week</th>
      <th>What</th>
      <th>Where</th>
      <th>When</th>
    </tr>
  </thead>
  <tbody>
    <!-------------------- MODULE 1 -------------------->
    <tr><th /><th>Digital Signal Processing</th><th /><th /></tr>
    <!-------------------- WEEK 1 -------------------->
    <tr>
      <td align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16712/">1</a></td>
      <td align="center">Основы цифровой обработки сигналов: понятие сигнала; концепции ЦОС; дискретизация по времени/амплитуде, теорема отсчётов; хранение, обработка и передача; сигналы дискретного времени; энергия и мощность; алгоритм Карплуса-Стронга.</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/01-intro-to-dsp/01_intro_to_dsp.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/RS4iK1zU7w4"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td>19.02.2021</td>
    </tr>
    <!-------------------- WEEK 2 -------------------->
    <tr>
      <td rowspan="2" align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16713/">2</a></td>
      <td align="center">Представление сигналов в спектральной области, понятие спектра, прямое и обратное преобразование Фурье, быстрое преобразование Фурье, оконное преобразование Фурье, банк фильтров, вычисление мел-частотных кепстральных коэффициентов.</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/02-frequency-domain/02_frequency_domain.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/OdmLyM0XRwA"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td rowspan="2">26.02.2021</td>
    </tr>
    <tr>
      <td align="center">Работа с аудиофайлами в Python, гармонические сигналы, свёртка, алгоритм Карплуса-Стронга.</td>
      <td align="center"><a href="https://nbviewer.jupyter.org/github/Illumaria/made-speech-signal-processing/blob/master/02-frequency-domain/lab_01.ipynb"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a><a href="https://nbviewer.jupyter.org/github/Illumaria/made-speech-signal-processing/blob/master/02-frequency-domain/lab_02.ipynb"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a></td>
    </tr>
    <!-------------------- WEEK 3 -------------------->
    <tr>
      <td rowspan="2" align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16714/">3</a></td>
      <td align="center">Цифровые фильтры, ЛИС-фильтры, _z_-преобразование, нерекурсивные и рекурсивные фильтры, теорема о свёртке; адаптивная фильтрация, банк фильтров и inception-блок, понижение частоты дискретизации и _pooling_, рекурсия и фильтрация в методе моментов, голосовая биометрия, мел-частотные кепстральные коэффициенты, синтез фильтров.</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/03-digital-filters-and-machine-learning/03_digital_filters.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/03-digital-filters-and-machine-learning/04_dsp_and_machine_learning.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/NoB1nJrK0Dk"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td rowspan="2">05.03.2021</td>
    </tr>
    <tr>
      <td align="center">Импульсная и переходная характеристики фильтров, АЧХ, ФЧХ; анализ спектрограммы, мел-шкала и мел-фильтры, классификация слов.</td>
      <td align="center"><a href="https://nbviewer.jupyter.org/github/Illumaria/made-speech-signal-processing/blob/master/03-digital-filters-and-machine-learning/lab_03.ipynb"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a><a href="https://nbviewer.jupyter.org/github/Illumaria/made-speech-signal-processing/blob/master/03-digital-filters-and-machine-learning/lab_04.ipynb"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a></td>
    </tr>
    <!-------------------- MODULE 2 -------------------->
    <tr><th /><th>Automatic Speech Recognition</th><th /><th /></tr>
    <!-------------------- WEEK 4 -------------------->
    <tr>
      <td align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16715/">4</a></td>
      <td align="center">Понятие речи, типы систем распознавания речи и сценарии их использования, метрики оценки качества (SER, WER, accuracy, FR, FA), трудности при создании; акустические признаки речи (MFCC); системы распознавания речи на основе сравнения с эталоном (DTW, token-passing).</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/04-intro-to-asr/04_intro_to_asr.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/ziWNTI7GTxg"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td>12.03.2021</td>
    </tr>
    <!-------------------- WEEK 5 -------------------->
    <tr>
      <td rowspan="2" align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16716/">5</a></td>
      <td align="center">Вероятностная постановка задачи распознавания речи, акустическая модель (цепь Маркова, скрытая марковская модель), языковая модель (n-grams, perplexity, discounting, back-off, ARPA LM, NN LM), лексикон, декодер, сбор и подготовка данных для обучения.</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/05-speech-recognition-systems/05_speech_recognition_systems.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/kmGWuDkF4mE"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td rowspan="2">19.03.2021</td>
    </tr>
    <tr>
      <td align="center">Реализация Dynamic Time Warping (DTW) алгоритма на основе Token Passing Algorithm (TPA).</td>
      <td align="center"><a href="https://nbviewer.jupyter.org/github/Illumaria/made-speech-signal-processing/blob/master/05-speech-recognition-systems/dtw_tpa.ipynb"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a></td>
    </tr>
    <!-------------------- WEEK 6 -------------------->
    <tr>
      <td align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16717/">6</a></td>
      <td align="center">Скрытые марковские модели (HMM), применение HMM для распознавания речи, смеси гауссовских распределений, обучение GMM-HMM.</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/06-gmm-hmm/06_gmm_hmm.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/4THZbCQ0-tM"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td>26.03.2021</td>
    </tr>
    <!-------------------- WEEK 7 -------------------->
    <tr>
      <td rowspan="2" align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16718/">7</a></td>
      <td align="center">Взвешенные конечные преобразователи, WFST-декодер, словные сети, дискриминативное обучение GMM-HMM, адаптация систем распознавания речи. Традиционные системы распознавания речи на основе нейронных сетей: нейросети как классификаторы.</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/07-dnn-hmm/07_dnn_hmm.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/0w5rukVuUos"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td rowspan="2">02.04.2021</td>
    </tr>
    <tr>
      <td align="center">Распознавание по эталонному словарю.</td>
      <td align="center"><a href="https://nbviewer.jupyter.org/github/Illumaria/made-speech-signal-processing/blob/master/07-dnn-hmm/recognition_via_reference_dictionary.ipynb"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a></td>
    </tr>
    <!-------------------- WEEK 8 -------------------->
    <tr>
      <td rowspan="2" align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16719/">8</a></td>
      <td align="center">Тандемные (TRAP, LC-RC, Bottleneck-признаки) и гибридные (CD-DNN-HMM) системы распознавания, обучение DNN-HMM (CLDNN, TDNN), последовательно-дискриминативное обучение (MMI, LF-MMI, MWE/MPE, sMBR), адаптация систем распознавания речи на основе нейронных сетей (VTLN, fMLLR-преобразование, дикторо-осведомлённое обучение, LIN, LHN, LON).</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/07-dnn-hmm/07_dnn_hmm.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/acSCesSywQw"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td rowspan="2">09.04.2021</td>
    </tr>
    <tr>
      <td align="center">DNN классификатор.</td>
      <td align="center"><a href="https://nbviewer.jupyter.org/github/Illumaria/made-speech-signal-processing/blob/master/08-dnn-classifier/dnn_classifier.ipynb"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a></td>
    </tr>
    <!-------------------- WEEK 9 -------------------->
    <tr>
      <td align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16720/">9</a></td>
      <td align="center">Недостатки современных гибридных систем, Connectionist Temporal Classification (CTC), RNN-Transducer (RNN-T), Encoder-Decoder системы с механизмом внимания (AED), комбинации end-to-end подходов.</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/09-end-to-end-asr-systems/09_end_to_end_asr_systems.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/acSCesSywQw"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td>16.04.2021</td>
    </tr>
    <!-------------------- WEEK 10 -------------------->
    <tr>
      <td rowspan="2" align="center"><a href="https://data.mail.ru/curriculum/program/lesson/16721/">10</a></td>
      <td align="center">Факторы искажения речи и способы борьбы с ними (разнообразие стилей речи, меж- и внутридикторская вариативность, разнообразие условий записи), снижение вариативности входных данных (VTLN, шумоподавление, дереверберация), повышение вариативности обучающих данных (Multi-Condition Training, data augmentation).</td>
      <td align="center">
        <a href="https://github.com/Illumaria/made-speech-signal-processing/blob/master/10-speech-distortion-factors/10_speech_distortion_factors.pdf"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/pdf.png" /></a>
        <a href="https://youtu.be/HV-ck7u2ZXs"><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/youtube.png" /></a>
      </td>
      <td rowspan="2">23.04.2021</td>
    </tr>
    <tr>
      <td align="center">End-to-end ASR system, ESPnet.</td>
      <td align="center"><a href=""><img src="https://github.com/Illumaria/made-deep-learning/blob/master/icons/jupyter.png" /></a></td>
    </tr>
  </tbody>
</table>