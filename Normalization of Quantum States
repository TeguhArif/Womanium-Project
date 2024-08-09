# Here are the vector representations of |0> and |1>, for convenience
ket_0 = np.array([1, 0])
ket_1 = np.array([0, 1])

def normalize_state(alpha, beta):
    """Compute a normalized quantum state given arbitrary amplitudes.

    Args:
        alpha (complex): The amplitude associated with the |0> state.
        beta (complex): The amplitude associated with the |1> state.

    Returns:
        np.array[complex]: A vector (numpy array) with 2 elements that represents
        a normalized quantum state.
    """
    
    # Calculate the normalization factor
    norm_factor = np.sqrt(np.abs(alpha)**2 + np.abs(beta)**2)
    
    # Normalize the amplitudes
    alpha_normalized = alpha / norm_factor
    beta_normalized = beta / norm_factor
    
    # Return the normalized state vector
    return np.array([alpha_normalized, beta_normalized])

# Example usage
alpha = 3 + 4j
beta = 1 - 2j
normalized_state = normalize_state(alpha, beta)
print("Normalized State:", normalized_state)
