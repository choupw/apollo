
load("//tools/install:install.bzl", "install", "install_src_files")

package(
    default_visibility = ["//visibility:public"],
)


install(
    name = "mock_install",
    type = "neo",
    deps = ["//third_party/tf2:install","//third_party/can_card_library:install","//third_party/camera_library:install","//third_party/rtklib:install","//modules/common_msgs:install","//cyber:install","//modules/common:install","//modules/transform:install","//modules/drivers/camera:install"],
)


install_src_files(
    name = "mock_install_src",
    type = "neo",
    deps = ["//third_party/tf2:install_src","//third_party/can_card_library:install_src","//third_party/camera_library:install_src","//third_party/rtklib:install_src","//modules/common_msgs:install_src","//cyber:install_src","//modules/common:install_src","//modules/transform:install_src","//modules/drivers/camera:install_src"],
)
