## Welcome to Category Adapted Enhancement with Weakly Labelled Data

**DEMOs are here!**

### Single-class enhancement: 
> Audios are picked from the test set (generated with the librispeech clean, MUSAN and Findsounds datasets).
> For simplicity, We pick **_Speech, Music, Animal and Vehicle_** (from 10 chosen classes mentioned in paper) enhancement as a demonstration.
> For each example, _noisy,seperated and clean_ audios are listed in order.

#### Speech Enhancement:
##### **Good** samples:

<audio style="width: 200px;" src="src/test/Speech/Good/mix_175.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Speech/Good/sep_175.wav" controls="controls">
</audio>

<audio style="width: 200px;" src="src/test/Speech/Good/mix_449.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Speech/Good/sep_449.wav" controls="controls">
</audio>

##### **Bad** samples:

<audio style="width: 200px;" src="src/test/Speech/Bad/mix_18.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Speech/Bad/sep_18.wav" controls="controls">
</audio>

#### Music Enhancement:
##### **Good** samples:

<audio style="width: 200px;" src="src/test/Music/Good/mix_31.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Music/Good/sep_31.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Music/Good/clean_31.wav" controls="controls">
</audio>

<audio style="width: 200px;" src="src/test/Music/Good/mix_747.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Music/Good/sep_747.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Music/Good/clean_747.wav" controls="controls">
</audio>

##### **Bad** samples:

<audio style="width: 200px;" src="src/test/Music/Bad/mix_328.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Music/Bad/sep_328.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Music/Bad/clean_328.wav" controls="controls">
</audio>

#### Animal Enhancement:
##### **Good** samples:

<audio style="width: 200px;" src="src/test/Animal/Good/mix_5.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Animal/Good/sep_5.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Animal/Good/clean_5.wav" controls="controls">
</audio>

<audio style="width: 200px;" src="src/test/Animal/Good/mix_124.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Animal/Good/sep_124.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Animal/Good/clean_124.wav" controls="controls">
</audio>

##### **Bad** samples:

<audio style="width: 200px;" src="src/test/Animal/Bad/mix_115.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Animal/Bad/sep_115.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Animal/Bad/sep_115.wav" controls="controls">
</audio>

#### Vehicle Enhancement:
##### **Good** samples:

<audio style="width: 200px;" src="src/test/Vehicle/Good/mix_81.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Vehicle/Good/sep_81.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Vehicle/Good/clean_81.wav" controls="controls">
</audio>

<audio style="width: 200px;" src="src/test/Vehicle/Good/mix_170.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Vehicle/Good/sep_170.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Vehicle/Good/clean_170.wav" controls="controls">
</audio>

##### **Bad** samples:

<audio style="width: 200px;" src="src/test/Vehicle/Bad/mix_104.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Vehicle/Bad/sep_104.wav" controls="controls">
</audio>
<audio style="width: 200px;" src="src/test/Vehicle/Bad/clean_104.wav" controls="controls">
</audio>

***

### Real video enhancement: 
> These videos are picked from the audioset eval. We enhance different audio categories (according to the sound classes appeared) with different category-adapted models. 
> 
> For each example, the original video is listed in the first. The rest are listed according to the original label order.

#### Case 1: (_Original sound label(s): Speech, Music_)

<video width="200" height="150" controls>
    <source src="src/audioset_eval/-1hDIl9Udkw_30.000_40.000.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/-1hDIl9Udkw_30.000_40.000_Speech.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/-1hDIl9Udkw_30.000_40.000_Music.mp4" type="video/mp4">
</video>


#### Case 2:(_Original sound label(s): Speech, Music_)

<video width="200" height="150" controls>
    <source src="src/audioset_eval/2j4m7JsNtNA_30.000_40.000.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/2j4m7JsNtNA_30.000_40.000_Speech.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/2j4m7JsNtNA_30.000_40.000_Music.mp4" type="video/mp4">
</video>

#### Case 3:(_Original sound label(s): Speech, Music, Horse_)

<video width="160" height="120" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000.mp4" type="video/mp4">
</video>
<video width="160" height="120" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000_Speech.mp4" type="video/mp4">
</video>
<video width="160" height="120" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000_Music.mp4" type="video/mp4">
</video>
<video width="160" height="120" controls>
    <source src="src/audioset_eval/3GbIhQLCH9I_16.000_26.000_Horse.mp4" type="video/mp4">
</video>

#### Case 4:(_Original sound label(s): Speech, Vehicle_)

<video width="200" height="150" controls>
    <source src="src/audioset_eval/4egukLBpAcQ_30.000_40.000.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/4egukLBpAcQ_30.000_40.000_Speech.mp4" type="video/mp4">
</video>
<video width="200" height="150" controls>
    <source src="src/audioset_eval/4egukLBpAcQ_30.000_40.000_Vehicle.mp4" type="video/mp4">
</video>

***

### Long film trailor enhancement:
> These videos are downloaded directly from youtube (long and uncut). We use our speech enhancement and music enhancement model (even with our typewriter enhancement model for real effect).

#### The Avengers 3: Infinite war

##### Original:

<video width="480" height="270" controls>
    <source src="src/trailor/AVG3.mp4" type="video/mp4">
</video>

##### Speech:

<video width="480" height="270" controls>
    <source src="src/trailor/AVG3_Speech.mp4" type="video/mp4">
</video>

##### Music:

<video width="480" height="270" controls>
    <source src="src/trailor/AVG3_Music.mp4" type="video/mp4">
</video>

#### Love Rosie:

##### Original:

<video width="480" height="270" controls>
    <source src="src/trailor/lvrs.mp4" type="video/mp4">
</video>

##### Speech:

<video width="480" height="270" controls>
    <source src="src/trailor/lvrs_Speech.mp4" type="video/mp4">
</video>

##### Music:

<video width="480" height="270" controls>
    <source src="src/trailor/lvrs_Music1.mp4" type="video/mp4">
</video>

#### The Greatest Showman:

##### Original:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref.mp4" type="video/mp4">
</video>

##### Speech:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref_Speech.mp4" type="video/mp4">
</video>

##### Music:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref_Music.mp4" type="video/mp4">
</video>

##### Typewriter:

<video width="480" height="270" controls>
    <source src="src/trailor/TGSM_ref_Typewriter.mp4" type="video/mp4">
</video>
