
def count_words_with_length(text, length):
    words = text.split()
    return sum(1 for word in words if len(word) == length)

if __name__ == "__main__":
    sentence = "Discipline and consistency build real progress"
    target_length = 7
    print(f"Sentence: {sentence}")
    print(f"Words with length {target_length}: {count_words_with_length(sentence, target_length)}")
