# Let's Program a Banjo Grammar

---

# Example

```python
def banjo_forward_roll(pitch, beats, chord='G'):
    if chord=='G': # TODO: other chords
        string1 = 'd'
        string5 = 'g'  
    pattern = itertools.cycle([pitch, string1, string5])
    return ''.join(next(pattern) for n in range(beats))
```

<audio controls="controls" class="fragment">
  <source src="wavs/cripple_creek_3.wav" type="audio/wav">
</audio>

---

# Next slide
- Blah
- Blah
- Blah
