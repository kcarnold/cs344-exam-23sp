ordinary_cross_entropy_with_logits does both sigmoid & binary crosss_entropy in a single function, WHERE BCEloss calculate cross_entropy on a one_hot_encoded_target w/o initial sigmoid.
