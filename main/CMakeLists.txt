
#
# Main component of TF Micro project 'micro_speech'.
#

idf_component_register(
    SRCS main.cc no_micro_features_data.cc yes_micro_features_data.cc model.cc
    PRIV_REQUIRES esp-nn esp-tflite-lib spi_flash
    INCLUDE_DIRS "")
