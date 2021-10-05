## Welcome to Category Adapted Enhancement with Weakly Labelled Data

DEMOs are here!

### single-class enhancement: audios are picked from the test set (generated with the librispeech clean, MUSAN and Findsounds datasets)

Speech Enhancement:
Good samples:

<audio width="120" src="src/test/Speech/Good/mix_175.wav" controls="controls">
mix Speech
</audio>
<audio width="120" src="src/test/Speech/Good/sep_175.wav" controls="controls">
sep Speech
</audio>



### real video enhancement: these videos are picked from the audioset eval. We enhance different audio categories with different category-adapted models.

Original 1:(Original sound label(s): Speech, Music)

<video width="200" height="150" controls>
    <source src="src/audioset_eval/-1hDIl9Udkw_30.000_40.000.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/-1hDIl9Udkw_30.000_40.000_Speech.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/-1hDIl9Udkw_30.000_40.000_Music.mp4" type="video/mp4">
</video>


Original 2:(Original sound label(s): Speech, Music)

<video width="240" height="180" controls>
    <source src="src/audioset_eval/2j4m7JsNtNA_30.000_40.000.mp4" type="video/mp4">
</video>
<video width="240" height="180" controls>
    <source src="src/audioset_eval/2j4m7JsNtNA_30.000_40.000_Speech.mp4" type="video/mp4">
</video>
<video width="240" height="180" controls>
    <source src="src/audioset_eval/2j4m7JsNtNA_30.000_40.000_Music.mp4" type="video/mp4">
</video>

Original 3:(Original sound label(s): Speech, Music, Horse)

<video width="240" height="180" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000.mp4" type="video/mp4">
</video>
<video width="240" height="180" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000_Speech.mp4" type="video/mp4">
</video>
<video width="240" height="180" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000_Music.mp4" type="video/mp4">
</video>
<video width="240" height="180" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000_Horse.mp4" type="video/mp4">
</video>

Original 4:(Original sound label(s): Speech, Vehicle)

<video width="240" height="180" controls>
    <source src="src/audioset_eval/4egukLBpAcQ_30.000_40.000.mp4" type="video/mp4">
</video>
<video width="240" height="180" controls>
    <source src="src/audioset_eval/4egukLBpAcQ_30.000_40.000_Speech.mp4" type="video/mp4">
</video>
<video width="240" height="180" controls>
    <source src="src/audioset_eval/4egukLBpAcQ_30.000_40.000_Vehicle.mp4" type="video/mp4">
</video>

### long film trailor enhancement: these videos are downloaded directly from youtube (long and uncut). We use our speech enhancement and music enhancement model (even with our typewriter enhancement model for real effect).

The Avengers 3: Infinite war

Original:

<video width="480" height="270" controls>
    <source src="src/trailor/AVG3.mp4" type="video/mp4">
</video>

Speech:

<video width="480" height="270" controls>
    <source src="src/trailor/AVG3_Speech.mp4" type="video/mp4">
</video>

Music:

<video width="480" height="270" controls>
    <source src="src/trailor/AVG3_Music.mp4" type="video/mp4">
</video>

Love Rosie:

Original:

<video width="480" height="270" controls>
    <source src="src/trailor/lvrs.mp4" type="video/mp4">
</video>

Speech:

<video width="480" height="270" controls>
    <source src="src/trailor/lvrs_Speech.mp4" type="video/mp4">
</video>

Music:

<video width="480" height="270" controls>
    <source src="src/trailor/lvrs_Music1.mp4" type="video/mp4">
</video>

The Greatest Showman:

Original:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref.mp4" type="video/mp4">
</video>

Speech:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref_Speech.mp4" type="video/mp4">
</video>

Music:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref_Music.mp4" type="video/mp4">
</video>

Typewriter:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref_Typewriter.mp4" type="video/mp4">
</video>
